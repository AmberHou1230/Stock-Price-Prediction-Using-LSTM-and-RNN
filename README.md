# Stock-Price-Prediction-Using-LSTM-and-RNN

## Objective
* Throughout this project, We will learn how to preprocess and prepare the historical stock price dataset for training and testing our models.

* we will delve into the fundamentals of RNNs and LSTMs and explore their suitability for capturing temporal dependencies in stock price data.

* This project serves as an essential foundation for understanding and utilizing advanced deep-learning techniques in the context of financial forecasting.

## Overview
Stock price prediction plays a crucial role in financial markets, and accurate forecasts
can have significant implications for businesses, investors, and financial institutions.
Stock price prediction helps investors and fund managers make informed investment
decisions. By accurately forecasting future stock prices, investors can identify potential
opportunities for maximizing profits or minimizing losses. It enables them to allocate
their capital wisely and adjust their investment portfolios based on predicted price
movements.

Machine and Deep Learning have demonstrated their potential to enhance the stock price
prediction accuracy and assist investors, traders, and financial analysts in making
informed decisions. By leveraging ML techniques, businesses can gain valuable
insights, optimize investment strategies, and improve risk management in stock
market's complex and dynamic realm.

The prediction of stock prices is a challenging task due to the inherent complexity and
volatility of financial markets. Traditional methods often fail to capture the intricate
patterns and dependencies present in stock price data. However, RNN and LSTM
models have shown great potential in capturing **temporal dependencies** and making
accurate predictions in various time series forecasting tasks.

In this project, we will focus on implementing recurrent neural
networks (RNNs) and long short-term memory (LSTM) networks specifically for the task
of stock price prediction. 

## Data Description
* Historical stock prices for Apple Inc. (AAPL) is obtained from the Yahoo Finance API. It includes a comprehensive record of daily stock price data, capturing the opening, closing, highest, and lowest prices, as well as the
trading volume for each trading day

## Tech Stack 
* Language: Python

* Libraries: keras, tensorflow, statsmodels, numpy, pandas, yfinance, pandas datareader, pandas_ta

## Project Walkthrough

* Neural Networks Basics:
  - Review the basics of neural networks to understand their structure and functionality.
  - Building and Training Neural Networks with Keras on an Example Dataset
* Loading Time Series Data:
  - Obtain the time series data for stock prices from yahoo finance.
● Data Transformations:
○ Perform feature scaling or normalization to bring data into a consistent
range.
○ Overlapping window creation for training.
● Recurrent Neural Networks:
○ Model Building and Training
○ Sequence Generation and Evaluation
● LSTMs:
○ Model Building and Training
○ Sequence Generation and Evaluation
● Multivariate Input and LSTMs
○ Creating Technical Indicators
○ Creating Labels
○ Perform feature scaling or normalization to bring data into a consistent
range.
○ Model Building and Training
○ Evaluation
