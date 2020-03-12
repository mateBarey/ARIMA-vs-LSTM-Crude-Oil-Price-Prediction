# ARIMA-vs-LSTM-Crude-Oil-Price-Prediction

Model Takes Crude Oil Prices from 2010 and to 2020 and uses a LSTM and ARIMA model to forecast the Price.

LSTM model is a recurrent Neural network that works by extracting the generalized features of a set, in this case a time series

sequence. The other model used was a ARIMA model which is a combination of Autogregressiion (Wchich expresses curren values

of a time series linearly in terms of its previous and values and residuals) and a MA model which expresses current value

of a time series lienarly in terms of its current and previsous residual values.

The RMSE error was evaluated and the ARIMA model was able to predict the test set with greater accuracy.
