

Project Overview
This project predicts and forecasts stock prices using deep learning. We focus on Apple Inc. (AAPL) historical stock prices from 2010 to 2025. A Stacked LSTM (Long Short-Term Memory) neural network is trained to learn patterns in past stock prices and then used to:

Predict prices on unseen data (test set)

Forecast future stock prices for the next 30 days

Key Features

Data fetched automatically using yfinance

Preprocessing with MinMaxScaler for better LSTM performance

Stacked LSTM with 3 layers for learning complex time-series patterns

Plots comparing actual vs predicted prices

Calculates RMSE to measure prediction accuracy

Produces a 30-day future stock price forecast

Getting Started

Clone or download the repository.

Open the .ipynb notebook in Google Colab or Jupyter Notebook.

Install required libraries (if not already installed):

pip install numpy pandas matplotlib scikit-learn tensorflow yfinance


Run all cells step by step.

Check plots for prediction accuracy and future stock price forecast.

Results

The model closely follows historical stock price trends.

RMSE shows the accuracy of predictions.

The 30-day forecast provides a possible trend for AAPL stock prices.

Project Structure
Stock-Price-Prediction-LSTM/
│
├─ Stock_Price_Prediction.ipynb   # Main notebook
├─ README.md                      # Project description
├─ requirements.txt               # Required libraries
