# Yahoo_finance_projects

In this project we used Long Short Term Memory (LSTM) to predict stock price of Amazon.

## Long Short Term Memory (LSTM)

Sequence prediction problems have been around for a long time. They are considered as one of the hardest problems to solve in the data science industry. These include a wide range of problems,from predicting sales to finding patterns in stock markets data, from understanding movie plots to recognizing your way of speech, from language translations to predicting your next word on your iPhone’s keyboard.

An Artificial Neural Network may learn to predict the stock prices based on a number of features: the volume of the stock, the opening value etc. While the price of the stock depends on these features, it is also largely dependent on the stock values in the previous days. In fact for a trader, these values in the previous days (or the trend) is one major deciding factor for predictions.

LSTMs are widely used for sequence prediction problems and have proven to be extremely effective. The reason they work so well is because LSTM is able to store past information that is important, and forget the information that is not. LSTM has three gates:

- The input gate: The input gate adds information to the cell state
- The forget gate: It removes the information that is no longer required by the model
- The output gate: Output Gate at LSTM selects the information to be shown as output

## Project structure
1. Downloading stock price Amazon data from yahoo using yfinance
2. Visualizing data set (matplotlib)
3. Preparing data set for model (scaling)
4. Using LMST model


# Results
![result](https://user-images.githubusercontent.com/77289083/108724791-04858b80-7526-11eb-8d8f-6d3e23c32950.png)
