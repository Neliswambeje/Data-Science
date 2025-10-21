# Credit Risk Classification

## Overview

This notebook demonstrates a full classification workflow to predict loan default. It includes data preprocessing, baseline Random Forest modeling, evaluation, and model explainability using SHAP.

## Notebook Contents

1. Load credit dataset (or use synthetic fallback)
2. Preprocess & feature engineering
3. Train/test split
4. Baseline Random Forest model
5. Evaluate using classification report and ROC AUC
6. Explain model with SHAP and export plots

## How to run

* Place `credit_data.csv` in the working directory if available.
* Install SHAP via `pip install shap` if needed.

## Presentation notes

* Emphasize how SHAP explains top predictors of default.
* Discuss model trade-offs and next steps (calibration, threshold tuning, cost-sensitive learning).

