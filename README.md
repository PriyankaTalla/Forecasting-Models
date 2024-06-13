## Below are the list of Timeseries Forecasting-Models covered in this repository with example

1. Moving Average (MA)
Concepts: Simple averaging over a rolling window.
Mathematical Topics:
Statistics: Mean, smoothing, rolling averages
Example: Forecasting monthly sales based on previous months.
Example: Forecasting daily temperatures using a 7-day moving average.

2. Exponential Smoothing
Concepts: Weighted averages over all previous observations.
Mathematical Topics:
Statistics: Exponential decay, smoothing parameters,  weighted sums, level smoothing
Example: Forecasting quarterly GDP based on previous observations.
Example: Predicting quarterly sales using single exponential smoothing.

3. Autoregressive (AR) Model
Concepts: Predicts the value at time t based on previous values.
Mathematical Topics:
Statistics: Autocorrelation function (ACF), partial autocorrelation function (PACF).
Example: Forecasting monthly sales using an AR(2) model.

4. Moving Average with Exogenous Variables (ARMAX)
Concepts: Includes external variables in addition to the time series data.
Mathematical Topics:
Statistics: Covariance, model specification.
Example: Forecasting monthly sales with advertising expenditure as an exogenous variable.

6. Autoregressive Integrated Moving Average (ARIMA)
Concepts: Time series decomposition, stationarity.
Mathematical Topics:
Statistics: Autocorrelation, differencing.
Linear Algebra: Matrix operations (for linear equations).
Example: Forecasting daily stock prices based on historical data.

7. Seasonal ARIMA (SARIMA)
Concepts: Incorporates seasonal components into ARIMA.
Mathematical Topics:
Statistics: Seasonal differencing, seasonal autoregression, seasonal moving average.
Example: Forecasting quarterly sales with seasonal trends using SARIMA.

8. Facebook Prophet
Concepts: Additive time series modeling with seasonality.
Mathematical Topics:
Statistics: Piecewise linear trend estimation, seasonality modeling.
Example: Forecasting daily website traffic using Prophet.

9. Seasonal Decomposition of Time Series (STL)
Concepts: Trend, seasonal components, residuals.
Mathematical Topics:
Statistics: Decomposition methods (e.g., STL).
Example: Forecasting monthly electricity consumption.

10. Seasonal Decomposition of Time Series (STL)
Concepts: Decomposes time series into seasonal, trend, and residual components.
Mathematical Topics:
Statistics: Seasonal decomposition, time series decomposition.
Example: Analyzing and forecasting quarterly sales using STL decomposition.


11. Vector Autoregression (VAR)
Concepts: Multivariate time series, lagged variables.
Mathematical Topics:
Linear Algebra: Matrix operations (for VAR coefficients).
Statistics: Multivariate regression.
Example: Forecasting macroeconomic variables like GDP, inflation, and unemployment.

6. Vector Autoregression (VAR)
Concepts: Models multiple time series variables together.
Mathematical Topics:
Linear Algebra: Matrix operations, eigenvalues.
Example: Forecasting sales and inventory levels simultaneously using VAR.

12. Long Short-Term Memory (LSTM) Networks
Concepts: Deep learning, sequential data modeling.
Mathematical Topics:
Neural Networks: LSTM architecture, backpropagation through time.
Optimization: Gradient descent.
Example: Forecasting daily temperature based on historical weather data.

13. Long Short-Term Memory (LSTM) for Time Series Forecasting
Concepts: Recurrent neural network architecture for sequence prediction.
Mathematical Topics:
Linear Algebra: Matrix operations, activation functions.
Optimization: Backpropagation through time.
Example: Time series forecasting of monthly sales using LSTM.

14. Gaussian Processes
Concepts: Bayesian modeling, non-parametric regression.
Mathematical Topics:
Probability: Gaussian distributions, kernel functions.
Optimization: Bayesian inference.
Example: Forecasting stock prices with uncertainty estimation.

