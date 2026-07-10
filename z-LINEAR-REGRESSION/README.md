# NLIC Stock Price Predictor

A Python-based financial data pipeline that analyzes historical stock data for **Nepal Life Insurance Company (NLIC)** to predict the next day's closing behavior. 

This project implements **feature engineering for dual-target modeling**:
1. **Regression Task:** Predicting the exact numerical price of the next day's close in Nepalese Rupees (NPR).
2. **Classification Task:** Labeling whether the market will move up tomorrow compared to today's closing price.

## 📈 How It Works & Feature Engineering

The script handles specific financial data formatting and creates time-shifted lookahead targets:

* **Datetime Parsing:** Converts raw date strings into proper pandas `datetime` format.
* **Target Creation:** 
  * `Next_Close`: Uses `.shift(-1)` to bring tomorrow's closing price back into today's row as the numerical target ($y_{reg}$).
  * `Direction`: Compares tomorrow's closing price against today's close, converting it to binary form (`1` for Up, `0` for Down/Flat) to serve as the classification target ($y_{clf}$).
* **Time-Series Split:** Splits the data chronologically (80% Train / 20% Test) using `shuffle=False` to prevent data leakage and simulate a real-world trading deployment.
* **Data Standardization:** Employs a `StandardScaler` to ensure features with differing magnitudes (e.g., volume vs. price) don't distort linear models.

