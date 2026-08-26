# Project 1

This workspace contains notebooks for NYC taxi/ride-hailing demand modeling: data preparation, exploratory analysis, weather/spatial feature enrichment, and predictive modeling.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Files
- `EDA.ipynb`: Spark-based data preparation and exploratory analysis, including Negative Binomial GLM modeling (statsmodels)
- `Weather.ipynb`: weather and spatial feature enrichment (geopandas, Open-Meteo)
- `Predictive_model.ipynb`: predictive modeling with XGBoost and scikit-learn evaluation metrics