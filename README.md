# Stock-Market-Prediction-Using-Reinforcement-Learning-and-Sentiment-Analysis

## Introduction

This project aims to predict the stock price movement of major companies in S&P500 and create
a model that can yield profits in the real market by performing two main schools of stock analysis
– fundamental analysis and technical analysis. We use two different machine learning methods
including text sentiment analysis and reinforcement learning with actor-critic algorithms.
For fundamental analysis which focuses on the economic and financial factors in the market, we
expect that reflecting financial news will show good performance since it contains the most recent
and important information about the market. We have created three sentiment analysis models
with different algorithms that determine whether given news data are positive, neutral, or
negative. Our models are based on the assumption that positive sentiment indicates that the
current image of the target stock is good, therefore, the investors’ attitude may be favourable and
the price may rise. For negative sentiment, it may apply as the opposite. Two of the models are
pre-trained while the other has been trained exclusively with Naïve Bayes algorithm and the data
collected by us.

For technical analysis that looks at statistical trends and patterns of stocks, we have created two
models which not only predict the movement of stock prices but also simulate automatic trading
based on the predictions and yield actual profits. The models are based on different
reinforcement learning algorithms including the famous variants of Actor-Critic methods –
Advantage Actor Critic (A2C) and Actor Critic using Kronecker-Factored Trust Region (ACKTR).
The models were trained upon 10 years of the trend information of the target stocks including
opening price, high, low, closing price (OHLC), and trading volume and then tested with the data
from the most recent year. We tried adjusting the discount factor of each model to see how it
affects the performance on long-term and short-term predictions.

Full report available here: https://drive.google.com/file/d/1PoHYElMpIMdCjpIliZdGWJv1-zrc8JcH/view?usp=sharing
