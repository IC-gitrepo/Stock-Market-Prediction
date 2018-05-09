# Stock-Market-Prediction
Predicting future stock prices with Recurrent Neural Network and its variants

Dependencies- Python v3.6.3, NumPy v1.14.0, TensorFlow v1.4.0, scikit-learn v0.19.1, matplotlib v2.1.0, fix_yahoo_finance v0.0.19, pandas v0.22.0, pandas_datareader v0.5.0

stock_features.ipynb- feature engineering- computed 8 technical indicators (rolling statistics) from 15 year Nasdaq Inc. stock data. Processed data stored in NasdaqInc_stockdata_features.csv

RNNs, LSTM-RNNs and GRU-RNNs were trained on this data. Given the prices of the past few days, predict the prices for the next day. 


