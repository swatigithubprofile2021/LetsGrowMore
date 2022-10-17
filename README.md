# LetsGrowMore
October Batch 2022
Data Set link :- https://raw.githubusercontent.com/mwitiderrick/stockprice/master/NSE-TATAGLOBAL.csv
This project focuses on techniques and tools for handling Time Series Datasets. Main aim of this project is to make Stock Market Prediction and Forecasting using Stacked LSTM.

⚫ Time series data is data that is recorded over consistent intervals of time.

⚫ Time Series Datasets consist of more than one attributes depending on DateTime attribute of our dataset.

⚫ Long short-term memory (LSTM) is an artificial neural network used in the fields of artificial intelligence and deep learning.

    There are  variety of recurrent neural networks (RNNs) that are capable of learning long-term dependencies, especially in sequence
    prediction problems. LSTM has feedback connections, i.e., it is capable of processing the entire sequence of data, apart from 
    single data points such as images.
Two approaches for solving this problem
i) Univariate Time Series Analysis : univariate time series model here means that there are only one dependent variable on 
    the time series model

ii) Multivariate Time Series Analysis: it consist of more than one time-dependent variable and each variable depends not only 
    on its past values but also has some dependency on other variables.
I've used Univariate Analysis Approach Choosing 'Closing Price' as dependent/Target Value.
STEPS :
    1) Importing Libraries and Loading data
    2) Cleaning data and sorting data by date.
    3) Applying univariate approch by selecting `Closing Price` as target variables.
    4) Exploration and Analysis of Datasets 
    5) Scaling by MinMax Scaler.
    6) Preparing train and test datasets.
    7) Constructing Stacked LSTM model of 3 layers.
    8) Evaluation of Model.
    9) Forecasting for future 30 days.
    10) Acknowledgement and References.
