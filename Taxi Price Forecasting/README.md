# Taxi Order Forecasting

This project focuses on forecasting the number of taxi orders for the next hour using historical data from an airport taxi service.

## Dataset

The dataset (`taxi.csv`) contains hourly taxi order counts (`num_orders`) from March to August 2018.

## Project Goals

- Analyze the time series of taxi orders.
- Engineer features relevant for time series forecasting.
- Train and evaluate machine learning models to predict hourly taxi orders.
- Achieve an RMSE metric of less than 48 on the test set.

## Main Steps

1. Data loading and hourly resampling.
2. Exploratory data analysis and visualization.
3. Feature engineering (day of week, hour, holiday indicator, lags, rolling mean).
4. Model training and hyperparameter tuning (Ridge Regression, LightGBM).
5. Model evaluation and result analysis.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- holidays
- lightgbm

