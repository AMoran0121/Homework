# I'm not going to start trading yen, nothing to do with this analysis I just don't have any experience in the FX market.

## Time Series Analysis

Historical Yen data since 1992 shows an upward trend with volatility.

The ARMA model performed better then the ARIMA model based on AIC and BIC scores.  I would not consdier the ARIMA model given the higher AIC and BIC results (which honestly might be driven by user error).

Garch model is showing higher trending forecasted volatility over the next 5 days.


## Regression Analysis

Plotting the first 20 predictions vs. true values gives charts that appear to be an inverse of each other so that is not building confidence.  

Conclusion is that the model is underfit because the In-Sample RMSE is larger than the Out-of-Sample RSME.  Options to improve fit include adding more data, adding more parameters / complexity and increasing the training set.
