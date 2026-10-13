# Time Series Analysis and Forecasting

## Overview

A collection of **academic practical assignments** completed during Applied Mathematics and Computer Science engineering studies at CY Tech. The exercises explore time series decomposition, trend and seasonality analysis, synthetic data generation, and linear regression using Python.

These notebooks are coursework exercises, not an independent end-to-end research project. Some work was completed in collaboration with Noé François.

## Contents

| Folder | File | Topic |
|---|---|---|
| Time-Series | `Time_Series_Decomposition.ipynb` | Seasonal decomposition and trend estimation using an autoroute dataset (fourth data column) |
| Time-Series | `Time_Series_Decomposition_Variant.ipynb` | Alternative analysis of the fifth data column |
| Time-Series | `Synthetic_Time_Series.ipynb` | Generating synthetic time series with trend, seasonality and noise |
| Regression | `Seasonal_Linear_Regression.ipynb` | Regression with seasonal indicators, NumPy and scikit-learn |


## Technologies

Python, Jupyter Notebook, NumPy, Pandas, Matplotlib, Statsmodels and scikit-learn.

## Getting Started

1. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Open Jupyter from the `TP1-Time-Series` directory when running the autoroute notebooks, so that the relative path to `autoroute.csv` resolves correctly:

   ```bash
   cd Time-Series
   jupyter notebook
   ```

   For the regression exercise, open the notebook in `Regression`.


