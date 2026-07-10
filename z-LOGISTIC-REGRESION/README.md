# Market Direction Predictor Using Logistic Regression

A Python-based machine learning pipeline that uses **Logistic Regression** to predict whether a trend (e.g., stock price, index, or economic indicator) will move **Up** or stay **Down/Flat**.

This project implements a strict time-series approach to data splitting and utilizes balanced class weighting to overcome the common majority-class guessing trap.

## 🚀 How It Works (The Pipeline)

The script processes data chronologically to predict future directions based on past historical features:

1. **Feature Extraction:** Separates the predictive clues (`X`) from the target direction (`y`).
2. **Time-Series Split:** Splits data into 80% Training and 20% Testing using `shuffle=False` to maintain the integrity of the timeline (preventing the model from "peeking" into the future).
3. **Data Standardization:** Uses `StandardScaler` to normalize features of different magnitudes so they are treated equally by the model.
4. **Balanced Classification:** Deploys a `LogisticRegression` model with `class_weight="balanced"`. This prevents the model from lazily guessing the most frequent historical outcome by heavily penalizing errors on rare events.
5. **Evaluation:** Outputs a comprehensive `classification_report` showing Precision, Recall, and F1-Score for both directional movements.


