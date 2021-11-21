# LSTM-Stock-Predictor
LSTM Stock Predictor

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](file:///C:/Users/aelri/Downloads/Price%20Plot%20vs%20Predicted%20for%20closing%20price.PNG)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Evaluate the performance of each model

Which model has a lower loss?

A:LSTM Closing Stock Predictor has a lower loss.

Which model tracks the actual values better over time?

A:Closing price predictor model tracks the actual values better over time.

Which window size works best for the model?

A: Loss @ window size of 10 is 0.0174

   Loss @ window size of 5 is 0.0075

   Loss @ window size of 1 is 0.0032

   Window size of 1 day works best for the model.
