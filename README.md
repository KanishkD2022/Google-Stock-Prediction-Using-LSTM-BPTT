# Google-Stock-Prediction-Using-LSTM-BPTT

This project aims to analyze and forecast the stock prices of Google (GOOG) using deep learning techniques, specifically leveraging a **Long Short-Term Memory (LSTM) neural network**. The **dataset GOOG.csv** contains historical stock data including Open, High, Low, Close, Volume, and Adjusted Close values, which are used to uncover patterns and predict future price movements.

Traditional machine learning models often struggle with capturing temporal dependencies in sequential data like stock prices. To overcome this limitation, we employ an LSTM model, a type of Recurrent Neural Network (RNN) designed to handle long-range dependencies and preserve context across time steps. LSTMs are particularly well-suited for time series prediction because they can learn trends and patterns from past data while managing the vanishing gradient problem typically faced by standard RNNs.

The model is trained using **Backpropagation Through Time (BPTT)** and optimized with **Gradient Descent**. These techniques ensure that the network effectively updates its weights across multiple time steps, learning meaningful representations of stock price behavior over time.
