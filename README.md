# Time-Series-Modeling
Box Jenkins Methodology

Abstract:

An analysis of the annual precipitation of rainfall in inches over the entire Great Lakes area,
Michigan. The experiment uses the "Box-Jenkins Methodology" to fit an autoregressive
integrated moving average model ARIMA(p,d,q) to the given time series, for the purpose of
forecasting future levels of precipitation. The "Box-Jenkins Methodology" requires a
stationary series that accounts for any seasonality present in the data. This approach
identifies the best ARMA model(s) to select when constructing the model.

The "Great Lakes" data set is an example of a non-seasonal, non-stationary time series that
experiences a slight upward linear trend. The series is differenced and transformed using
"Box-Cox" in order to stabilize the mean and variance, correcting for stationarity. The best
model fitted for the data was an ARIMA(4,1,0) found by observing the partial and auto
correlation functions. The fit suggested the best estimates for the coefficients via the AIC.
Verified as independent random variables, the residuals of the fitted model were tested for
normality using the McLeod-Li, Ljung-Box, and Shapiro-Wilk test. The model proved to be
an adequate representation of the data providing reasonable predictions for precipitation.

