# Forecasting manufacturing capacity utilization
This project forecasts capacity utilization of US manufacturing firms by training and testing a time series data from 2001 to 2024. The results were compared with the traditional ARIMA model. 

## Methods
- Tree-based machine learning models (Random Forests and Gradient Boosting) were used with hyperparameter tuning.
- ARIMA model was used for comparison.
- Data was split into 90%-10% for training and testing respectively.
- For Gradient Boosting, a grid search was performed to obtain the optimal set of parameters (no. of trees and learning rate)
- MAPE and RMSE was used as evaluation metrics. 

## Tools
- Python, Jupyterlab, pandas, numpy, matplotlib, seaborn, sklearn

## Key results
- Machine learning models outperformed the ARIMA model in terms of both MAPE and RMSE.
- Out of ML models, Gradient Boosting Machine outperformed the Random Forests Model in terms of both MAPE and RMSE.
- Most important predictors were identified from a set of internal firm-level variables and a set of external risk indicators

