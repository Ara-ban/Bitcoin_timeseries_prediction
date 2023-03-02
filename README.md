# Bitcoin_timeseries_prediction

This project explores the use of two different methods for time series prediction on Bitcoin prices: the ARIMA model and a Recurrent Neural Network (RNN) implemented with TensorFlow and Keras.

# Data

The data used in this project was provided by Capgemini and consists of daily Bitcoin prices in USD from September 2011 to May 2021.

# Methods

The first method used to predict Bitcoin prices was the ARIMA model, which is a commonly used time series forecasting method that takes into account the autocorrelation and seasonality of the data. The second method used was an RNN implemented with TensorFlow and Keras, which is a more advanced method that is able to capture complex patterns in the data.

# Results

After training both models on the Bitcoin price data, we found that the RNN method was able to achieve a higher level of accuracy in predicting future prices compared to the ARIMA model. This suggests that the RNN method may be better suited for predicting Bitcoin prices than traditional time series models.

# Trading Bot

As a final step, we implemented a simple trading bot that uses the RNN model to predict future Bitcoin prices and makes buy/sell decisions based on those predictions. This bot is meant to be used for demonstration purposes only and should not be used for actual trading.

# Libraries Used

The following libraries were used in this project:

TensorFlow
Keras
Statmodels
Scikit-learn (sklearn)
These libraries were used for various tasks including data preprocessing, model training and evaluation, and implementing the trading bot.

# Conclusion

This project demonstrates the use of two different methods for time series prediction on Bitcoin prices, and shows that the RNN method is able to achieve higher accuracy than traditional methods like ARIMA. It also provides an example of how these models can be used in a practical application such as a trading bot, and highlights the importance of exploring different libraries and methods when working with time series data.
