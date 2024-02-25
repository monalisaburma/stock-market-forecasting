# stock_market_fore# Stock Market Forecasting using LSTM

## Overview

This project utilizes Long Short-Term Memory (LSTM) networks for stock market forecasting. The goal is to predict stock prices based on historical data using a sequential deep learning model.

## Project Structure

- **Stock_market_forecasting.ipynb**: Jupyter Notebook containing the code for the project.
- **README.md**: This file, providing an overview of the project.

## Dataset

The dataset (`AAPL.csv`) consists of historical stock prices for Apple Inc. The data includes features such as Open, High, Low, Close, and Volume.

## LSTM Model

The project employs LSTM, a type of recurrent neural network (RNN), to capture temporal dependencies in the stock price data.

## Model Training

The dataset is split into training and testing sets. The LSTM model is trained on the training set, and its performance is evaluated on the test set.

## Results

The model's performance is evaluated using Mean Squared Error (MSE) on both the training and test datasets. The obtained results are as follows:
- Training Data MSE: 142.44
- Test Data MSE: 237.93

## Forecasting

The model is then used to forecast stock prices for the next 30 days. The predicted values are compared with the actual stock prices.

## Usage

For detailed instructions and code, refer to the Jupyter Notebook `Stock_market_forecasting.ipynb`.

## Plots

![Stock Price Forecasting](https://github.com/monalisaburma/stock-market-forecasting/assets/122416015/954ad89e-7a95-4b0d-9518-7cca31e9166f)

Complete o/p:
![image](https://github.com/monalisaburma/stock-market-forecasting/assets/122416015/078521e1-76a8-4824-b62f-37fcf3af7691)



Feel free to reach out for any questions or suggestions!
casting
