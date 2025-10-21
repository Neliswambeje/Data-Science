# Anomaly Detection in Time Series

## Overview

This notebook demonstrates detecting anomalies in a time series using Isolation Forest and feature engineering. It includes synthetic data generation with injected anomalies for demonstration.

## Notebook Contents

1. Create synthetic time series (or load real data)
2. Feature engineering (rolling mean/std)
3. Fit Isolation Forest to detect anomalies
4. Visualize anomalies on time series
5. Export anomaly labels for downstream review

## How to run

* Use `timeseries.csv` if you have real data, otherwise notebook uses synthetic data.

## Presentation notes

* Explain choice of features and contamination parameter.
* Show how detected anomalies match injected events.
