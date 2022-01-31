# Week-10---Time-Series-Analysis
Imports:
1. pandas
2. numpy
3. imblearn
4. hvplot
5. sklearn


Regression analysis
Assessing viability of using lagged returns as a predictor for present returns, in an effort to display the existence of autocorrelation in the time-series data.

- Seperated data in to train and test, with train independent information being lagged returns and the dependent variable being present returns

- Tested the model predictive ability in-sample performance and out-sample performance

Time series analysis
Used differing algorithms on the CAD-JPY price time-series from 1982 to 2020.
- Initially decomposed the price data from 2015 onwards, using a Hodrick-Prescott filter, into trend and noise plots, to more easily analyse the trends of the data.

- Made data stationary by retrieving the percentage change of the time-series, forecasted price movements using ARMA.

- Using raw price data, added a layer of depth by ensuring stationarity was held in time series data, using ARIMA, to difference the data

- Forecasted volatility fluctuations using the GARCH model
