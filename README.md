# AAPL_Stock_Model
Machine learning model for Apple Stocks using historical data from csv file.

**Environment**

Conda

Matplot-lib
Numpy
Pandas
Scikit-learn
Torch
Torchvision

And all dependent libraries

**Model**

Python script that uses the Pytorch based deep learning neural network to derive a Long Short Term Memory (LSTM) predictive model with Mean Squared Error (MSE) as a measure of error.

Reads csv file with historical stock data on date, opening price, high price, low price, and closing price sourced from MarketWatch. Data encompasses approximately a one year period. Uses pandas dataframe to prepare data, before converting data into torch data sets. Learning rate set at 0.01 with 100 epochs.
