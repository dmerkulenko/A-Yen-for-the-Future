# A-Yen-for-the-Future - Time Series Analysis
![Yen Photo](Images/unit-10-readme-photo.png)

## Background

The financial departments of large companies often have to make foreign currency transactions when doing international business, while hedge funds are also interested in anything that will provide an edge in predicting currency movements. Hence, both are always eager to gain a better understanding of the future direction and risk of various currencies. 

In this time series analysis, I am testing many time series tools to predict future movements in the value of the Canadian dollar versus the Japanese yen.

## Analysis Breakdown

[Time-Series Forecasting](time_series_analysis.ipynb)

[Linear Regression Modelling](regression_analysis.ipynb)

- - -

## Analysis Conclusion

In this time series analysis, ARIMA and ARMA were seen as not reliable prediction models for CAD-JPY returns. Both show low statistical significance threshold (0.05 or lower). 

The GARCH model on the other hand, showed promissing results and thus, reliability. It's three out of four p-values show high statistical stability.Thus showing reliability in the forecast of increasing volatility for CAD-JPY returns in the near term.

In terms of linear regression analysis, the model for predicting CAD-JPY returns performs better in out-of-sample than in-samle because of its lower RMSE score (0.84).
