# 🌳 Classification using Machine Learning

This project demonstrates the implementation and comparison of four popular supervised machine learning classification algorithms using Python and Scikit-learn.

The project includes two datasets:

- 🩺 **Breast Cancer Wisconsin Dataset** (Medical Classification)
- 📈 **NABIL Stock Dataset** (Stock Market Direction Prediction)

The objective is to understand how different classification algorithms perform on datasets with different characteristics.

---

## 📌 Algorithms Used

- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM - RBF Kernel)
- K-Nearest Neighbors (KNN)

---

# 🩺 Dataset 1: Breast Cancer Wisconsin

## About

The Breast Cancer Wisconsin dataset is a built-in dataset provided by Scikit-learn.

It contains measurements computed from digitized images of breast mass cell nuclei and is used to classify tumors as:

- Malignant
- Benign

This dataset is widely used for learning and benchmarking classification algorithms.

---

## Features

The dataset contains **30 numerical features**, including:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Worst Radius
- Worst Area
- Worst Perimeter
- and more...

Target Variable:

- 0 → Malignant
- 1 → Benign

---

## Workflow

- Load dataset from Scikit-learn
- Train-test split
- Feature scaling using StandardScaler
- Train four classification models
- Compare model performance
- Visualize Decision Tree
- Analyze Random Forest feature importance
- Perform Cross Validation

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report
- Cross Validation Score

---

# 📈 Dataset 2: NABIL Stock Market

## About

This project predicts whether the **next trading day's closing price** will move **Up** or **Down** based on historical stock market data of **NABIL Bank** listed on the Nepal Stock Exchange (NEPSE).

Instead of predicting the exact stock price, this project performs **binary classification**.

Target Variable:

- 0 → Down / Flat
- 1 → Up

---

## Features Used

- Open
- High
- Low
- Volume
- MA20 (20-Day Moving Average)
- MA50 (50-Day Moving Average)

---

## Feature Engineering

The following features were created before training:

- Next Day Closing Price
- Direction (Up/Down)
- Moving Average (20 Days)
- Moving Average (50 Days)

Direction was generated using:

```python
Direction = (Next_Close > Close).astype(int)
```

---

## Workflow

- Load cleaned NABIL dataset
- Data preprocessing
- Feature engineering
- Handle missing values
- Train-test split
- Standardization
- Train four classification models
- Compare performance
- Visualize Decision Tree
- Plot Random Forest Feature Importance

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

# 📊 Models Compared

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Each model was trained and evaluated using the same preprocessing pipeline for a fair comparison.

---

# 📚 Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Project Structure

```
CLASSIFICATION (Decision Tree, Random Forest, SVM, KNN)
│
├── BREASTCANCER.ipynb
├── NABIL.ipynb
├── README.md
```

---

# 🎯 Learning Outcomes

Through this project, I learned:

- Difference between supervised classification algorithms
- Feature scaling using StandardScaler
- Decision Tree visualization
- Random Forest feature importance
- Cross Validation
- Performance comparison using multiple evaluation metrics
- Binary classification on real-world stock market data
- Building complete machine learning classification pipelines

---

# 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- ROC Curve and AUC Score
- Precision-Recall Curve
- XGBoost and LightGBM
- CatBoost
- More NEPSE stock datasets
- Time-series based classification models

---

## 👨‍💻 Author

Developed as part of my **Data Science & Machine Learning** learning journey using Python and Scikit-learn.