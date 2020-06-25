# Time Series Project

## Part 1 - Linear Models

### Dataset description:
The file “2014-2018 PM10 LisAvLib” contains a time series of hourly-levels of PM_10 particles (in micrograms per cubic meter), collected at Avenida da Liberdade monitoring station in Lisbon from 01/01/2014 to 31/12/2018.

### Main Goal:
Fit a SARIMA-type model to the time series representing 24-hour average levels of PM_10 particles. 

### Process:
1. Exploratory Data Analysis:
    1. Handling Missing Values;
    2. Statistical and Empirical Analysis;
    3. ACF and PACF;
    4. Decomposing;
    5. Identification of the dependence of orders and degree of differencing;
    6. Transformations.
2. Model Fitting and Diagnostics:
    1. Parameter Estimation;
    2. Residual diagnostics and model selection.
3. Cross-validation;
4. Forecast:
    1. Forecast the data into the future up to 5 time periods ahead;
    2. Calculate 95% prediction intervals for each of the 5 forecasts.

### Code Language: Python 3.0

## Part 2 - Non-Linear Models

### File Description:
The file "2015-2019 Nasdaq.txt" contains the date, open, high, low, closing, adjusted close and volume values of the Nasdaq composite index from 02/01/2015 to 30/12/2019.

### Main Goals:
1. Calculate the time series of log-returns associated to the daily closing values of the Nasdaq Composite Index.
2. Fit the best GARCH-type model to the time series of log-returns.

### Process:
1. Exploratory Data Analysis:
    1. Log-returns;
    2. Differencing;
    3. ACF and PACF analysis;
    4. Independence Testing;
    5. Fitting ARIMA-type model.
2. GARCH-type model fit:
    1. ARCH model;
    2. GARCH model;
    3. APARCH model.
3. Residuals Diagnostic.

### Code Language: R
