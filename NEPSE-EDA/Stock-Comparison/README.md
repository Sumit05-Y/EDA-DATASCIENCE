# 📊 NEPSE Stock Comparison - Exploratory Data Analysis (EDA)

## 📌 Overview

This project presents an **Exploratory Data Analysis (EDA)** comparing the one-year historical stock performance of **NABIL Bank**, **Nepal Life Insurance Company (NLIC)**, and **Nepal Telecom (NTC)** using data from the **Nepal Stock Exchange (NEPSE)**.

The primary objective is to clean and prepare the datasets, normalize stock prices, and compare their performance over the same time period.

---

## 📂 Datasets

**Datasets Used**

- NABIL Bank (NABIL)
- Nepal Life Insurance Company (NLIC)
- Nepal Telecom (NTC)

**Source:** Nepal Stock Exchange (NEPSE)

Each dataset contains historical stock market information, including:

- Trading Date
- Open Price
- High Price
- Low Price
- Closing Price
- Previous Closing Price
- Volume
- Number of Transactions

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Analysis Performed

### 1. Data Loading

- Loaded historical stock datasets for NABIL, NLIC, and NTC.
- Imported each dataset into a Pandas DataFrame.

### 2. Data Cleaning

- Converted the **Date** column to datetime format.
- Cleaned the **Volume** column by replacing invalid values and converting it to numeric format.
- Removed unnecessary columns such as **Symbol** and **Turn Over**.
- Sorted each dataset chronologically.

### 3. Data Preparation

- Combined the closing prices of all three companies into a single dataset.
- Used the trading date as the common index for comparison.

### 4. Stock Price Normalization

- Normalized the closing prices by setting each stock's first trading day's closing price to **100**.
- This allows all three stocks to be compared fairly despite having different price ranges.

### 5. Comparative Analysis

- Compared the normalized stock prices over time.
- Evaluated the relative growth and performance of each company during the one-year period.

---

## 📈 Key Insights

- Data cleaning ensures consistency across all datasets.
- Normalization enables direct comparison between stocks with different market prices.
- Comparing normalized closing prices helps identify which stock performed better over the selected time period.
- Combining multiple datasets provides a broader perspective on market trends within NEPSE.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Load multiple datasets.
- Clean and preprocess financial data.
- Handle missing and inconsistent values.
- Merge datasets for comparative analysis.
- Normalize stock prices.
- Compare historical stock performance.
- Interpret financial data using Python.

---

## 🚀 Future Improvements

Possible enhancements include:

- Line charts for normalized stock prices.
- Daily return analysis.
- Percentage change calculations.
- Moving Average (MA) analysis.
- Volatility comparison.
- Correlation heatmaps.
- Risk vs Return analysis.
- Predictive modeling using Machine Learning.

---

## 📚 Skills Demonstrated

- Data Loading
- Data Cleaning
- Data Preprocessing
- Data Transformation
- Dataset Merging
- Financial Data Analysis
- Stock Price Normalization
- Comparative Data Analysis
- Exploratory Data Analysis (EDA)

---

## 📄 Dataset Credit

This project uses historical stock market data from the **Nepal Stock Exchange (NEPSE)**.

**Official Website:**  
https://www.nepalstock.com/

The datasets are used solely for educational and portfolio purposes. All market data belongs to the Nepal Stock Exchange and its respective data providers.

---

## 📌 Conclusion

This project applies Exploratory Data Analysis techniques to compare the historical stock performance of **NABIL Bank**, **Nepal Life Insurance Company (NLIC)**, and **Nepal Telecom (NTC)**. Through data cleaning, normalization, and comparative analysis, the project demonstrates how multiple financial datasets can be prepared and analyzed to gain meaningful insights into stock market performance using Python and Pandas.