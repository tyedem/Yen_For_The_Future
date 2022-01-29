# A Yen For The Future

![Yen Photo](Images/unit-10-readme-photo.png)

## Background

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies. 

- - -

- - -
## Analysis Summary
In this time series analysis, ARMA and ARIMA have not proven to be reliable prediction models for returns. The statistical significance threshold is set at 0.05 or lower. ARIMA has no p-values sitting at or below this threshold. ARMA's first autoregression and moving average lags both meet this threshold for statistical significance. However, it should be noted that the AIC and BIC scores for ARIMA score lower than ARMA. Thus, conflicting and casting doubt over the reliability of ARMA's fit over ARIMA.

In predicting volatility, GARCH's p-values are highly significant at omega, alpha[1] and beta[1], while only alpha[2] shows insignificance. Thus, there is some reliability in its forecast that volatility will increase in the near term.

In this linear regression analysis, the model for predicting returns performs better in out-of-sample data compared to in-sample data by scoring a rounded RMSE score of 0.64 versus the in-sample RMSE score of 0.84.
- - -
- - -
## Resource
https://medium.com/analytics-vidhya/interpreting-arma-model-results-in-statsmodels-for-absolute-beginners-a4d22253ad1c

