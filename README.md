# Google Stock Prices Prediction using LSTM RNN

This repository contains a machine learning model built with LSTM (Long Short-Term Memory) Recurrent Neural Network (RNN) to predict the future stock prices of Google. The model utilizes historical stock price data from Jan 2012 to Dec 2016 to learn patterns and make predictions for the stock prices in Jan 2017 based on the sequence of past prices.

## Dataset

The dataset used for training and evaluation consists of historical daily stock prices of Google from Jan 2012 to Dec 2016. Each data point in the dataset includes the date, opening price, highest price, lowest price, closing price, and volume of traded shares.

## Model Architecture

The predictive model is built using LSTM RNN, which is a type of recurrent neural network specifically designed to capture long-term dependencies in sequential data. The model takes a sequence of historical stock prices as input and learns to predict the future stock prices.

The architecture of the LSTM RNN model includes multiple LSTM layers followed by fully connected layers for prediction. The model is trained using the training dataset and optimized using backpropagation and gradient descent.
