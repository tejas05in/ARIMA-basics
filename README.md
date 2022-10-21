# ARIMA-basics
ARIMA model for sales forecasting 
  Time series: when all other factors are constant prediction of future values.
  Differenent Methods of doing Time series Analysis and Forecasting
  
	  ARIMA model. 
	  Seasonaly ARIMA.  Most used.
	  Holt Winter Exponential Smoothing.Easiest and effective model

1.	Important Concepts and terminology in Time series Analysis.
  Stationarity

A stationary time series is one whose properties(ie mean, variance, autocorrelation) does not depend on the time.
  Autoregression AR. 
  Moving Average MA
  Integration & Difference
    ACF and PACF Plots
  Time series components:
    Trend: long term smooth movement, upward or downward
    Seasonal: periodic fluctuation, less than 1 year, most commonly found in industry.
    Cyclical: periodic fluctuation, more than 1 year.
    irregularity: random movement.

## ARIMA is the Most common model used for time series forecasting. It has 3 components.
1.	Autoregression AR. 
2.	Moving Average MA
3.	Integrated

1.	Autoregression AR.
o	Future values of Y is dependent of previous lagged values of Y.
o	regression of yt on yt-1, yt-2 .
o	P = ORDER OF AR; current value of y is dependent on how many previous lagged value of current Y. if p=2 that means yt is dependent on yt-1 and yt-2.
o	P from PACF 
o	Interpretation of PACF: 
2.	Moving Average MA.
o	Future values of Y is dependent of previous lagged values of white noise ie the irregular component. white noise is just  the error. error is the differerence between the actual value and predicted value. so we take into considerration the error also to predict the future value.
o	autocorrelation between the errors.
o	Trend, s, c components of TS is captured in AR where as the irregular comp is captured in MA.
o	q is order of MA.
o	ACF gives q.

3.	Integrated
o	Intergrated means no of times we difference the data then we have to integrated it back to get the original series back.
o	We difference to remove trend and seasonality to it stationary series as only after making a series stationary we cam impliment AR and MA.
