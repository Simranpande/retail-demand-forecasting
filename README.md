# retail-demand-forecasting
# Predictive Retail Demand & Dynamic Pricing Engine

Time-series demand forecasting and a what-if pricing simulator for retail,
built on the M5 Forecasting (Walmart) dataset.

## Goal
Forecast daily unit sales, estimate price sensitivity, and turn forecasts into
inventory recommendations, with an interactive dashboard where users can test
discount and promotion scenarios.

## Dataset
[M5 Forecasting - Accuracy (Kaggle)](https://www.kaggle.com/competitions/m5-forecasting-accuracy)
Subset: store CA_1, top 100 items by sales. Raw data is not stored in this repo.

## Project structure
- `notebooks/` : Colab notebooks for each phase
- `src/` : reusable code (features, models)
- `app/` : Streamlit dashboard
- `reports/` : figures and the research paper

## Progress
- [x] Data cleaning and preparation
- [x] Exploratory data analysis
- [ ] Time-series decomposition (STL)
- [ ] Baseline models (seasonal naive, SARIMA)
- [ ] Prophet and XGBoost/LightGBM with lag features
- [ ] Price elasticity and inventory logic
- [ ] Streamlit what-if dashboard
- [ ] Research paper

## Status
Work in progress.
