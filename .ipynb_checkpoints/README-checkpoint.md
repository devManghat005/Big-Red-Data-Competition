# Donor Retention Prediction

This project uses historical donation data to predict whether a donor will donate again within 90 days of a previous donation. The model is trained using features like donation frequency, total donated amount, and recency.

## 📊 Features Engineered

- `frequency`: Number of times the donor has donated
- `total_amount`: Total amount the donor has contributed
- `recency_days`: How many days ago the donor last donated

## 🎯 Goal

Predict donor retention using a machine learning model (XGBoost), helping organizations improve their outreach and retention strategies.

## 📁 Files

- `main.py`: Main script that loads data, creates features, trains the model, and prints evaluation metrics.
- `Sam's Fans All Transactions All Time (1).xlsx`: Input Excel file with donation history.
- `README.md`: This documentation.

## 🧠 Model

The model used is `XGBClassifier` from XGBoost. It is trained on 80% of the data and tested on the remaining 20%. Evaluation is done using classification metrics.

## 📦 Requirements

- pandas
- numpy
- scikit-learn
- xgboost
- openpyxl (for reading Excel files)

Install dependencies with:
```bash
pip install -r requirements.txt
