# Sales Forecasting Notebook

## Overview

This notebook demonstrates time series forecasting using Prophet and ARIMA (statsmodels). It includes synthetic data fallback and instructions to run on real datasets.

## Notebook Contents

1. Load time series sales dataset (CSV with columns `ds` and `y`)
2. Visualize seasonal patterns and trends
3. Fit Prophet model and plot forecast
4. Fit ARIMA/SARIMA model and plot forecast with confidence intervals
5. Compare model outputs and evaluate

## How to run

* Place `sales.csv` with columns `ds` (date) and `y` (value) in working directory, or run with synthetic data.
* Install Prophet if necessary: `pip install prophet` or `pip install fbprophet` depending on environment.

## Presentation notes

* Show forecast plots and discuss uncertainty bands
* Explain model selection and performance comparison

