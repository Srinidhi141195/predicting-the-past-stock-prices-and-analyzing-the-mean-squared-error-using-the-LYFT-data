# predicting-the-past-stock-prices-and-analyzing-the-mean-squared-error-using-the-LYFT-data

Overview:
Recurrent Neural Netowkrs (RNNs) and the application of the time series and the sequential analysis. I have used the LYFT dataset for the 100 days to divide the data into 10 days and to predict the 10th day stock price using the previous 9 days prices. I have used Simple RNN, LSTM and the Conv1d models to predict the stock prices.

Inference:
From the above I have predicted the mean sqaured error and the actual and the 10 day predictions. From the above, just based of the MSE value, it can be clearly seen that the simple RNN is performing the best. It has the least mean squared error value of 0.38. As we start adding layers to it with LSTM, GRU etc, the error seems to increase. However it decreases with the conv1d but still out of all the models, the simple RNN is giving the best results so far but regardless, all the models are performing their best at predicting the stock prices with a very low mean sqaured error.

