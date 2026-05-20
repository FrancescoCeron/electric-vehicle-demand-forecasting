# Electric Vehicle Demand Forecasting

Academic project developed for the Business, Economic and Financial Data course at the University of Padova.
The project focuses on forecasting electric and hybrid vehicle registrations in the United Kingdom using different statistical and econometric time series models.
The analysis compares classical forecasting techniques with more flexible approaches capable of modeling nonlinear trends and incorporating macroeconomic variables.

## Methods

The following forecasting methods were implemented and compared:
- ARIMA / SARIMA
- ARIMAX
- Exponential Smoothing
- Generalized Additive Models (GAM).

The project also includes an exploratory implementation of the Bass diffusion model for technology adoption analysis.

## Dataset

The analysis uses quarterly UK vehicle registration data from 2016 to 2024.
Additional exogenous variables include:
- electricity consumption
- charging infrastructure
- petrol prices
- unemployment rate
- CPI indicators
- Bank of England interest rates
- Brent oil prices

## Main Findings

- Electric vehicle registrations show strong nonlinear growth dynamics
- Hybrid vehicle registrations exhibit a recent declining trend
- ARIMAX models improved forecasting performance by incorporating external variables
- GAM + ARIMA approaches provided flexible modeling of nonlinear patterns
- Damped Holt exponential smoothing achieved strong short-term forecasting performance

## Technologies
- R
- Forecast package
- mgcv
- Time Series Analysis
- Econometrics

## Authors
- Francesco Ceron
- Emanuele Cavaliero

