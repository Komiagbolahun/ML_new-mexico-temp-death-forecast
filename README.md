# new-mexico-temp-death-forecast
GRU/RF/XGBoost forecasting of temperature and mortality trends in New Mexico.
# New Mexico Climate & Mortality Forecasting

A machine learning project forecasting average temperature and death rate trends in
New Mexico using historical meteorological and public health data.

## Overview
- Built GRU (Gated Recurrent Unit) neural network models to forecast average temperature
  and mortality rate, using iterative multi-step forecasting: individual models predict
  each meteorological parameter forward in time, which then feed into the primary GRU model.
- Benchmarked GRU performance against Random Forest and XGBoost regressors.
- Data sourced from NOAA Climate Data Online and the New Mexico Department of Health.

## Tech stack
Python, TensorFlow/Keras, scikit-learn (RandomForest, XGBoost, preprocessing/scaling),
pandas, NumPy, Matplotlib.

## Team project
This was a team project completed as part of Modeling and code implementation. I thank Raji, A, Marina and Wooters, N for their contribution.


## Author
Muiz Adekomi — [github.com/Komiagbolahun](https://github.com/Komiagbolahun)
