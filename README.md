# Macroeconomic Forecasting with Time Series Models

This project focuses on forecasting GDP and other macroeconomic parameters using various time series models. The goal is to analyze the historical data, apply appropriate techniques to make the time series stationary, and develop accurate forecasting models.

## Table of Contents

- [Description](#description)
- [Dependencies](#dependencies)
- [Results](#results)


## Description

The project aims to forecast macroeconomic variables, such as GDP, by utilizing time series analysis techniques. The workflow includes the following steps:

1. **Exploratory Data Analysis (EDA)**: Conduct an in-depth analysis of the time series data, exploring its patterns, trends, and seasonality. Use visualization techniques, such as line plots, box plots, and heatmaps, to gain insights into the data.

2. **Stationarity Check**: Determine whether the time series data is stationary or exhibits non-stationarity. Apply techniques like the Augmented Dickey-Fuller (ADF) test to test for stationarity. If the data is non-stationary, perform differencing operations or take logarithms to achieve stationarity.

3. **Autocorrelation and Partial Autocorrelation Analysis**: Use the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots to identify significant lags in the data. These plots help in determining the order of autoregressive and moving average terms for the time series models.

4. **Spectral Analysis**: Conduct spectral analysis to identify the dominant frequencies present in the data. Plot the power spectrum to visualize the frequencies with higher amplitudes.

5. **Granger Causality Test**: Perform the Granger causality test to identify the dependencies between different time series variables. This helps in determining which variables can be used as predictors for forecasting.

6. **Univariate and Multivariate Time Series Analysis**: Apply univariate time series models, such as ARIMA (Autoregressive Integrated Moving Average), to individual variables. Additionally, use multivariate models like Vector Autoregression (VAR) and Vector Error Correction Model (VECM) to capture the interdependencies between variables.

7. **Model Evaluation**: Assess the accuracy and quality of the forecasting models using evaluation metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared. Compare the performance of different models and select the most accurate one.

8. **Residual Analysis**: Examine the residuals of the selected model to ensure they exhibit white noise properties. Plot the residuals and perform tests like the Durbin-Watson statistic to check the quality of the fit.

## Dependencies

This project relies on the following dependencies:

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- sklearn
- scipy

## Results

![image](https://github.com/jashshah-dev/Time-Series-Forecasting-of-Macro-Economic-Paramaters/assets/132673402/6a5a1f16-9cde-440b-b58a-78c74e2810a4)




