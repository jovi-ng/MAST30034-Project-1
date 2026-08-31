# Project 1

This workspace contains notebooks for NYC taxi/ride-hailing demand modeling: data preparation, exploratory analysis, weather/spatial feature enrichment, and predictive modeling.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Files
- `EDA.ipynb`: Spark-based data preparation and exploratory analysis, including Negative Binomial GLM modeling (statsmodels), including heat map for volume counts
- `Weather.ipynb`: weather and spatial feature enrichment (geopandas, Open-Meteo)
- `NB_GLMs.ipynb`: Train and evaluate Negative Binominal regression models. Three response variables (arrival, departure, within trip counts). Report MAE, RMSE, R^2
- `XGBoost_models.ipynb`: Train and evaluate XGBoost Tree models. Three response variables (arrival, departure, within trip counts). Report MAE, RMSE, R^2, feature importance. Plot Predicted vs. Actual results for each yearly hold out. 
