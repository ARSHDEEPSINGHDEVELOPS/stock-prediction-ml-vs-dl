#  ML vs DL for Stock Price Prediction
A Comparative Study Using Traditional Methods, Machine Learning Models, and LSTM Deep Learning Networks
## Overview
This repository presents a comprehensive comparison of traditional statistical methods, classical machine learning models, and deep learning LSTM architectures for stock price prediction. The analysis is based on Microsoft (MSFT) stock data from 2019 to 2024.

The work accompanies the research paper:
"Leveraging Machine Learning and Time Series Analysis for Stock Prediction: A Review"
Published in IEEE Conference 2024
Research Paper Link: [link](https://docs.google.com/document/d/1CTb1tz8a0Oc9kwlnLas6o7-wIyLWfj6G/edit?usp=sharing&ouid=115044931240553350004&rtpof=true&sd=true)

## Models evaluated include:
Traditional methods (Average, Weighted Average, Moving Average, Weighted Moving Average)
Machine Learning models (Linear Regression, Weighted Linear Regression, LASSO)
Deep Learning models (LSTM with multiple configurations)
The project aims to compare accuracy, performance, and model behavior for time-series forecasting tasks.

## Techniques Implemented
1. Traditional Methods 
Simple Average
Weighted Average
Moving Average (MA)
Weighted Moving Average (WMA)

2. Machine Learning Models
Linear Regression
Weighted Linear Regression
LASSO Regression

3. Deep Learning Model
Long Short-Term Memory (LSTM) networks
Variations tested:
Activation functions: tanh, sigmoid, relu
Filter sizes: 32, 64
Multi-layer architectures

## Dataset
Source: Yahoo Finance
Ticker: Microsoft (MSFT)
Duration: January 2019 to May 2024
Features Used: Date, Close
A univariate time-series forecasting structure is used to enable fair comparison between all models.

## Key Findings
1. Traditional methods showed large deviations and weak forecasting accuracy.

2. Machine learning models performed moderately, with LASSO showing the best performance among ML models.

3. LSTM significantly outperformed all other models due to its ability to capture sequential dependencies.

4. LSTM models using ReLU activation and 64–64 layer configuration provided the lowest error values.

## Why LSTM Performs Better
1. Captures long-term sequential patterns in stock price data.

2. Memory cell structure retains historical information.

3. Learns complex non-linear relationships naturally.

4. More robust to noisy data compared to linear ML models.

## Future Enhancements

1. Integrating technical indicators such as RSI, EMA, MACD, Bollinger Bands
2. Implementing multivariate LSTM forecasting
3. Exploring GRU, BiLSTM, and Transformer-based architectures
4. Hyperparameter tuning using Grid Search or Optuna
5. Creating a real-time stock prediction dashboard
