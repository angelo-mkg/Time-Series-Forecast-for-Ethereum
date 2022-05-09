# Eth-Time-Series-Forecast

RNN/SARIMA time series forecasting models to predict weekly trends of ETH closing price

# Business Problem

Develop a forecasting model that accurately predicts ETH closing price every 7 days

# The Data

Historical time series data downloaded from Tradingview.com (start date: Oct 10, 202019, end date: April 3, 2021)

# Repository Contents

1. ETH.csv - Raw data downloaded from Tradingview.com
2. ETH RNN Forecast.ipynb - Python notebook with Recurrent Neural Network Models
3. ETH ARIMA Forecast.ipynb - Python notebook with ARIMA Models
4. Best Iterations.xlsx - Best pdq and PDQS combinations for ARIMA Model, including MSE and RMSE
5. Models - folder containing best RNN Models

# Results

1. ETH RNN Models achieved USD RMSE of USD 60 to 96 (current price at USD 3,498)
2. ETH ARIMA Models achieved USD RMSE of USD 125 to 141 (current price at USD 3,498)
3. Models established confirmed upward trend
