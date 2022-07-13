# bitcoin-prediction-deeplearning
Attempt at predicting sharp raises in Bitcoin price using Deep Learning and technical indicators as features

I tried to predict raises in BTC/USD using price data from 2017 to this day. I got the price data from Yahoo Finance (python package called yfinance) and calculated technical indicators from that price data with pandas.ta (https://github.com/twopirllc/pandas-ta).

I tried to predict good spots for long trading in bitcoin price using sequential Deep Learning model with one hidden layer and some regularization. The target had two classes: BTC/USD has risen 10% in the 5 days or not. The results of the model are not nearly good enough to use them with a trading bot for example.

Possibly target modification or somehow getting more data (even though I used all the data possible from BTC/USD) could improve the results.
