# README

* Yanan ZHOU
* adreambottle@outlook.com
* +971 522570360

## All files

```
.
├── Main_Process.ipynb
├── Classic_Prediction_Framework.ipynb
├── LSTM_Dev_Process.ipynb

├── ARIMA.py                  
├── LSTM.py
├── Prophet.py
├── NeuralNetwork.py
├── NNmodel.py

├── Toolkits.py
├── Classic.py
├── main.py
├── LSTM_Simulate.py

├── README.md
├── requirements.txt
├── Cohorts_rev.csv
├── data_use.csv
├── decompose_dict.json

```


## Main Assignments files

* `Main_Process.ipynb`  The main process of data clean, data visualization, data mining and machine learning. I have built 4 differnt models using `ARIMA(Auto-Arima)`,` LSTM(by Keras)`, `Prophet(by Facebook Prophet)` and `NeuralNetwork(by Pytorch)`. They have been ecapsulated in the same format, and can be called in the same way.

* `Classic_Prediction_Framework.ipynb`  Build a time series forecasting framework based on sklearn. The framework can call different models from sklearn, including: `"knn", "random forest", "adaboost", "gbrt", "support vector machine regression", "lasso", "decision tree", "linear", "ridge", "echo net"`

* `LSTM_Dev_Process.ipynb` The develop process of train, test and predict the data by using keras

## Models

Models here are encapsulated into the same form can be called by the main process

* `ARIMA.py`
* `LSTM.py`
* `Prophet.py`
* `NeuralNetwork.py`
* `NNmodel.py`  => PyTorch models for `NeuralNetwork.py`， including MLP, CNN, RNN different kind of models

## Other Scripts

* `Toolkits.py`  =>  Main functions used in the project are stored
* `LSTM_Simulate.py` => The original python codes for `LSTM_Dev_Process.ipynb`
* `main.py` => The original python codes for `Main_Process.ipynb`
* `Classic.py` => The original python codes for `Classic_Prediction_Framework.ipynb`

## Files

* `requirements.txt` => Libraries and Environment. You can use `pip install -r requirements`
* `Cohorts_rev.csv` => Original Data
* `data_use.csv` => Cleaned Data, using for reload data
* `decompose_dict.json` => Time Series Decomposition Data, using for transfer data
