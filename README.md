# Time Series Forecasting with RNN and LSTM

## Overview
This project demonstrates time series forecasting using Recurrent Neural Networks (RNNs) and Long Short-term Memory (LSTM) models. It analyzes financial time series data, focusing on patterns such as trends and moving averages, and prepares the data to predict stock prices.

Key features include:
- **Simple Moving Average (SMA):** Analysis of optimal window sizes (e.g., 10-day and 20-day moving averages) for trend identification.
- **RNN and LSTM Implementation:** Capturing short-term and long-term dependencies in the data.
- **Data Preparation:** Sequences created from previous days' stock prices to predict future prices.

## Dataset
The notebook treats stock prices as a time series challenge. 10 years's data of google has taken from yahoo finance by using yfinance library. Data preprocessing includes splitting the dataset into training, testing, and validation sets (80%, 10%, and 10%, respectively).

## Key Steps
1. **Moving Average Analysis:**
   - Calculate SMAs for various periods.
   - Determine optimal durations for noise reduction and trend capture.

2. **Data Preparation for RNN/LSTM:**
   - Create input-output sequences using a 10-day window.

3. **Model Development:**
   - Define and train an LSTM model to forecast stock prices.
   - Evaluate model performance on test and validation datasets.

4. **Visualization:**
   - Graphical analysis of moving averages and model predictions.

## Dependencies
- Python 3.10 or later
- TensorFlow and Keras
- NumPy and Pandas
- Matplotlib and Seaborn for visualizations

## Usage
1. Clone this repository and install the required dependencies.
2. Run the notebook step by step to:
   - Analyze trends using SMA.
   - Train the LSTM model on time series data.
   - Visualize the results.

## Results
The project highlights the effectiveness of LSTM models for time series forecasting, demonstrating strong performance in capturing sequential patterns and trends.
