# amex_default_prediction:
- The objective is to predict credit default by leveraging an industrial scale dataset form AMEX
- The dataset includes time-series behavioral data and anonymized customer profile information
- Access the raw data here: https://www.kaggle.com/competitions/amex-default-prediction/data

# Soution:
- Feature engineering
- XGBoost and LGBM (dart mode) as base layer models
- Stacked with XGBoost/LGBM at layer two
- bagged ensemble
