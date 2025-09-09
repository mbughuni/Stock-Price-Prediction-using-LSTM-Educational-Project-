# 📈 Stock Price Prediction using LSTM (AAPL)

## Overview

This project demonstrates how to use Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), to predict stock prices based on historical time-series data.
I used Apple Inc. (AAPL) stock data from Yahoo Finance to train and test the model. The goal is to predict the next 30 days of stock prices using past 60 days of historical data.
---
Objectives

Learn the basics of time-series forecasting using deep learning.

Build and train an LSTM model with TensorFlow/Keras.

Visualize historical vs predicted stock prices.

Understand limitations of LSTMs in financial forecasting.
## Technologies Used

Python 3.10

TensorFlow / Keras – Deep learning framework

NumPy / Pandas – Data handling

Matplotlib – Visualization

yfinance – Stock price data
## 🚀 Features

- Collects stock data using **yfinance**
- Scales and preprocesses data
- Builds an **LSTM model with Dropout layers**
- Predicts **next 30 days** of stock prices
- Visualizes actual vs predicted prices

---
## Dataset

Source: Yahoo Finance

## 📊 Example Plot

Here is a sample prediction result:

![Prediction Plot](plot.png)

---

## ⚙️ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/mbughuni/Stock-Price-Prediction-using-LSTM-Educational-Project-.git
cd stock-price-prediction
pip install -r requirements.txt
```
