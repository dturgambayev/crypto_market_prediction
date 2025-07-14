# 🧠 Crypto Market Prediction

This project aims to predict short-term cryptocurrency price movements using minute-level trading data and anonymized production signals.

## 📂 Project Structure

- `notebooks/` – Jupyter notebooks for EDA, modeling, and final submission
- `data/` – Training/test data (excluded from repo)
- `submission.csv` – Final prediction file

## 🚀 Model

We used CatBoostRegressor with carefully engineered features, including order flow signals and rolling volume metrics. The final model achieved a validation Pearson correlation of **0.10885**.

## 🛠️ Tech Stack

- Python 3.10+
- CatBoost
- scikit-learn
- Pandas, NumPy, Seaborn

## 🧪 Notebooks

1. **01_eda_and_feature_analysis** – Exploratory data analysis and correlation checks
2. **02_feature_engineering_and_modeling** – Feature creation and model training
3. **03_submission_and_analysis** – Test prediction and submission file generation

## 📈 Evaluation Metric

- Pearson Correlation between predicted and true values.

## 🤝 Acknowledgement

Inspired by DRW's crypto market modeling challenge on Kaggle.