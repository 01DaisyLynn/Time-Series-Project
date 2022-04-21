# Time-Series-Project

# Collaborators

Daisy Lynn Wanjiru

Kevin Kiprono

Obrein Telly

Brendah Koro

Francis Thairu

# Description

Many people are looking to buy shares and the stockmarket is the harbour for this, but before making this choice they need to know were the price is at or will be. In this Project will be looking into Google stock prices and analyzing their past stock  activity so as to build a model that can predict where their stock price will lay in the future

# Problem statement

Stock market price prediction is a fundamental exercise in Finance, Valuation, Accounting et al. The entire idea of predicting stock prices is to gain an added advantage in terms of gaining profits. Predicting how the stock market will perform is a hard task to do. There are other factors involved in the prediction, such as physical and psychological factors, rational and irrational behavior, and so on. All these factors combine to make share prices dynamic and volatile. This makes it very difficult to predict stock prices with high accuracy.  To do this, the market relies on historical data. For our purposes, we leverage publicly available data over a 5 year period to build a predictive model.

# Setup

Install and Import necessarry Libraries

Review dataset

Perform data cleaning

Exploratory data analysis

Develop models - LSTM(long short term memory) , FBprophet

# Tools used

Colab Notebook

Data - data was sourced from yahoo finance

# Libraries

import yfinance as yf

from yahoofinancials import YahooFinancials - for data

import mplfinance as mpl - for financial visualization

from tensorflow.keras.layers import LSTM - for LSTM model

import fbprophet
from fbprophet import Prophet - for fbprophet model

NOTE: the above libraries are just a portion of the libraries needed

# License

MIT license was used

Copyright (c)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files
