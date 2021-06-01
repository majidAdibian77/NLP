
## General info
This project is a simple next-word-prediction in persian language.

## Steps
* First of all, a file including a collection of Persian news is provided. This data is not so good and if you have a larger data, you can improve the results.
* Then data is preprocesed in data_preprocess.ipynb, for example replace arabic chars to persian. After that vectors of data and labels are saved.
* Then in train_model.ipynb saved data is loaded and a recerrent neural network is trained using LSTM layers.
  After 65 epochs accurecy in training data is 0.973 and change of accuracy and loss is ploted:
  
| accuracy      | loss      |
|------------|-------------|
| <img src="https://github.com/majidAdibian77/Next-word-prediction/blob/master/results/accurecy.png" width="250"> | <img src="https://github.com/majidAdibian77/Next-word-prediction/blob/master/results/loss.png" width="250"> |

* Then in test_model.ipynb saved model is loaded and model is tested to predict next word:

<img src="https://github.com/majidAdibian77/Next-word-prediction/blob/master/results/test_result.JPG" width="250">

## How to Improve
* The most important problem of this project is not using big and appropriate primary data. Accuracy improves dramatically if you use more appropriate primary data.
* Different parameters as well as different layers can be tested for the neural network model and the accuracy can be improved.
