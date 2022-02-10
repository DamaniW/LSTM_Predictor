# LSTM_Predictor

### Background

In this project I will develop and evaluate two custom Long Short-Term Memory Recurrent Neural Network models. The purpose of the models is to predict Bitcoin's (n)th day closing price based on a rolling (X) day window. The first model will use the Crypto Fear and Greed Index (FNG), which analyzes emotions and sentiments from different sources to produce a daily FNG value for cryptocurrencies. The second model will use Bitcoin closing prices. Each model will be evaluated on unseen, test data. Additionally, each model will be built in separate notebooks. The reason for this is, in order to make accurate comparisons between the two models, we need to maintain the same architecture and parameters during training and testing of each model.

### Evaluating the Performace of Each Model

Once the building, training, and testing proceedures have been successfully completed, we can see that the closing price model resulted in more accurate predictions. This finding is supported by the mean square error loss metric. The FNG model has a loss of 0.0916, and the closing price model has a lower loss of 0.0185. We can better visualize the performance by using a line chart to compare the real with the actual closing prices.

### Fear and Greed Index (FNG) Model

![alt text](https://github.com/DamaniW/LSTM_Predictor/blob/main/FNG_model.png?raw=true)

### Closing Price Model

![alt text](https://github.com/DamaniW/LSTM_Predictor/blob/main/Close_model.png?raw=true)
