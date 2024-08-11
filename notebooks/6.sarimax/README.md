# SARIMAX

- `SARIMAX` stands for **Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors**. It’s an extension of the `ARIMA` model that incorporates both seasonality and external variables (exogenous regressors) into the forecasting process. Here’s a breakdown of its components:
    - **Seasonal (S):** Captures periodic patterns in the data, such as weekly, monthly, or yearly cycles.
    - **Autoregressive (AR):** Represents the relationship between the current value and previous values in the time series.
    - **Integrated (I):** Involves differencing the data to make the time series stationary by removing trends and seasonality.
    - **Moving Average (MA):** Accounts for the dependency of the current value on past error terms.
    - **Exogenous Regressors (X):** Allows the inclusion of external variables that may affect the time series.

- SARIMAX is particularly useful for time series data that exhibits recurring patterns and is influenced by external factors.

- References:
    - [Complete Guide To SARIMAX in Python](https://www.geeksforgeeks.org/complete-guide-to-sarimax-in-python/)
    - [What Is a SARIMAX Model?](https://365datascience.com/tutorials/python-tutorials/sarimax/)
    - [SARIMAX model: What is it? How can it be applied to time series?](https://datascientest.com/en/sarimax-model-what-is-it-how-can-it-be-applied-to-time-series)
    - [SARIMAX & ARIMA forecasters](https://skforecast.org/0.9.1/user_guides/forecasting-sarimax-arima.html)