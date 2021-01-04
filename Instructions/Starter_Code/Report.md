
Time Series Analysis Portion

ARMA model:

Because the starter code guidance was to use order = (2,1.)  This means most of the trend is in 1 or 2 lags.  The plotted ARMA model shows potential yield over 5 days.  All yield is positive, which is a sign the yen is increasing in value, but we do see a drop in yield (still positive though) from ~0.012 to ~0.0055 during Day 1.  This indicates the value of yen is increasing.

ARIMA model:

ARIMA is considered more accurate at time series forecasting than the ARMA model.  ARIMA calcuates differences between a value and its previous value to detrend the series.  The starter code guidance was to use order = (5,1,1.)  The plotted ARIMA model shows a positive trend, which indicates that the value of yen is increasing

GARCH model:

GARCH is used to predict volatility.  the plotted GARCH model shows an upward trend, which means volatility (and risk) in the market is expected to rise over the next 5 days.

Regression Analysis Portion

When comparing the trend lines to see how the predicted return did in comparison to the actual return, the model did an okay job towards the end.

Out-of-Sample performance uses the testing dataset and the RMSE is 0.415 while in-sample performance uses the training dataset and the RMSE is 0.596

In-sample RMSE is slightly greater than out-of-sample RMSE in this case, which indicates that the model might be underfitting.  The two RMSE values are very close though, so its not very underfitted.
