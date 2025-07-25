# 🚴‍♂️ Time Series Forecasting: Bike Rentals in DC

In this project, I forecast daily bike rental demand using the [Capital Bikeshare dataset](https://www.kaggle.com/datasets/lakshmi25npathi/bike-sharing-dataset). I engineered time-aware features like lag values, rolling averages, and calendar attributes to train forecasting models.

## 📌 Goal
Predict the number of bike rentals each day using weather and time-based signals.

## 📊 Techniques
- Lag & rolling mean features
- Time-based train-test split
- Linear Regression & Random Forest comparison
- Model evaluation (MAE, RMSE, R²)
- Visualization of actual vs predicted demand

## 🧠 Key Insight
> In this case, Linear Regression outperformed Random Forest. Simpler models can be more effective when temporal signals are strong.

## 🧪 Final Results

| Model            | MAE     | RMSE    | R²    |
|------------------|---------|---------|-------|
| Linear Regression| \$709   | \$985   | 0.725 |
| Random Forest    | \$774   | \$1029  | 0.700 |

## 📁 Files
- `bike_rentals_forecasting.ipynb`
- `requirements.txt`

---
