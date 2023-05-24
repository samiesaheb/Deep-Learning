# Deep-Learning
Few notebooks I wrote learning Deep Learning

Few models used:

ARIMA: 
ARIMA, which stands for Autoregressive Integrated Moving Average is a popular time series forecasting model that combines three components:

Autoregression (AR): The autoregressive component captures the relationship between an observation and a certain number of lagged observations from the past. It assumes that the future value of a time series depends linearly on its previous values.

Integration (I): The integration component is used to make the time series stationary by differencing the observations. Stationarity refers to the property where the statistical properties of a time series, such as mean and variance, remain constant over time. Differencing helps remove trends or seasonality present in the data.

Moving Average (MA): The moving average component takes into account the dependency between an observation and a residual error from a moving average model applied to lagged observations. It helps to capture the short-term fluctuations or noise in the data.

ARIMA models are defined by three parameters: p, d, and q.

p represents the order of the autoregressive component (number of lagged observations).
d represents the degree of differencing (number of times differencing is performed to achieve stationarity).
q represents the order of the moving average component (number of lagged residual errors).
ARIMA models are widely used for time series forecasting, including applications in finance, economics, and other fields. They can capture both short-term and long-term dependencies in the data and provide valuable insights into future trends and patterns.

Linear Regression: 
In linear regression, the goal is to find the best-fitting line (or hyperplane in higher dimensions) that minimizes the difference between the predicted values and the actual values of the dependent variable. This line is determined by estimating the coefficients (or weights) assigned to each independent variable, as well as an intercept term.

