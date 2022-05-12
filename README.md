<h1 align="center">Predictive Analytics Projects</h1>

Predictive Analytics covers the area of time series analysis for various purposes. Often time series analysis is performed for the following:-
- Stock Market Analysis
- Sales Forecasting
- Weather Forecasting
- Predicting user trends

Through this repository I try to cover few major techniques used in time series analysis such as AR, MA, SARIMA, FB Prophet and LSTM.

## Description
Time series data is different than other structured data as in these type of datasets time plays the key role in determining a particular event. It captures the following aspects of a time series which we need to tackle before making the dataset ready for further analysis:-
- Dependence; observations are correlated
- Trend
- Seasonality
- Cyclic (Seasonal Persistence)

We need to ensure the given time series is stationary in order to use it for further analysis. A stationary time series:-
1. mean value function does not depend on time 't'
2. autocovariance function depends on 's' and 't' only through 's - t'

Key steps performed in converting a time series in a stationary format are:-
- Transformation
- Decomposition

I've covered various aspects of dealing with time series data through the usage of ACF plots or autocorrelation function, PACF plots or partial autocorrelation function, AR or autoregressive, MA or Moving average, ARMA or Autoregressive Moving Average, SARIMA, Fb Prophet and LSTM.

## Prerequisites and Installation
Time series analysis can be performed in R as well as Python using statsmodels modules.

- statsmodels
```
pip install statsmodels
```
- sktime
```
pip install sktime
```
- FbProphet
```
pip install Prophet
```

## Contents
[Predicting Google Trend Using Search Volume & Ads Spending](https://github.com/ShrutiL1396/Python/tree/main/Machine%20Learning%20Models) <br/>
[Weather Forecast](https://github.com/ShrutiL1396/Python/tree/main/Visualisations)

## Contact
Shruti Shivaji Lanke - <br/>
shrutilanke13@gmail.com or slanke1@student.gsu.edu <br/>
Project Link - <br/>
https://github.com/ShrutiL1396/Python
