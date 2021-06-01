
## General info
This project is a simple next-word-prediction in persian language.

## Steps
* First of all small persian news data is provided. This data is not so good and if you have a larger data, you can improve the results.
* Then data is preprocesed in data_preprocess.ipynb, for example replace arabic chars to persian. After that vectors of data and labels are saved.
* Then in train_model.ipynb saved data is loaded and a recerrent neural network is trained using LSTM layers.
  After 65 epochs accurecy in training data is 0.973 and change of accuracy and loss is ploted:
  | col 1      | col 2      |
|------------|-------------|
| <img src="https://media.wired.com/photos/5926db217034dc5f91becd6b/master/w_582,c_limit/so-logo-s.jpg" width="250"> | <img src="https://mk0jobadderjftub56m0.kinstacdn.com/wp-content/uploads/stackoverflow.com-300.jpg" width="250"> |