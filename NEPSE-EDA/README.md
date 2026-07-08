# 📈 NEPSE Exploratory Data Analysis (EDA)

This project contains Exploratory Data Analysis (EDA) of selected companies listed on the **Nepal Stock Exchange (NEPSE)**. Using historical stock market data, the project demonstrates data cleaning, preprocessing, trend analysis, and visualization techniques to better understand stock performance.

---

## 📂 Project Structure

```
NEPSE-EDA/
│
├── NABIL/
│   ├── EDAnabil.ipynb
│   ├── NABILONEYEARCSV.csv
│   └── README.md
│
├── NLIC/
│   ├── EDAnlic.ipynb
│   ├── NLICONEYEARCSV.csv
│   └── README.md
│
├── NTC/
│   ├── NEPSE(NTC).ipynb
│   ├── NTCONEYEARCSV.csv
│   └── README.md
│
├── Stock-Comparison/
│   ├── NEPSE_Stock_Comparison.ipynb
│   └── README.md
│
└── README.md
```

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on historical NEPSE stock data.
- Clean and preprocess raw stock datasets.
- Analyze stock price trends over time.
- Compare the performance of multiple NEPSE-listed companies.
- Visualize technical indicators for better market understanding.

---

## 🏢 Companies Included

- 🏦 NABIL Bank Limited
- 🛡️ Nepal Life Insurance Company Limited (NLIC)
- 📡 Nepal Telecom (NTC)

---

## 📊 Analysis Performed

### 🧹 Data Cleaning
- Imported and cleaned raw CSV datasets.
- Converted date columns into datetime format.
- Checked and handled missing values.
- Removed duplicate records.
- Sorted data chronologically.
- Prepared datasets for analysis.

### 📈 Closing Price Analysis
- Daily closing price trends.
- Identification of bullish and bearish movements.
- Long-term price visualization.

### 📉 Moving Average Analysis
Calculated and visualized:
- **20-Day Moving Average (MA20)**
- **50-Day Moving Average (MA50)**

These indicators help identify short-term and long-term market trends.

### 📊 Volatility Analysis
- Measured stock price fluctuations over time.
- Identified periods of high and low market volatility.

### 📊 Stock Comparison
The Stock-Comparison project includes:
- Closing Price Comparison
- 20-Day Moving Average Comparison
- 50-Day Moving Average Comparison
- Volatility Comparison
- Trend Analysis across multiple companies

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/EDA-DATASCIENCE.git
```

Navigate to the NEPSE project:

```bash
cd EDA-DATASCIENCE/NEPSE-EDA
```

Install the required dependencies:

```bash
pip install -r ../requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📂 Data Source

The historical stock market datasets used in this project were obtained from **Nepse Alpha**, which provides publicly available historical data for companies listed on the Nepal Stock Exchange (NEPSE).

**Source:**  
https://nepsealpha.com/nepse-data

The data is used solely for educational and exploratory data analysis purposes.

---

## 🚀 Future Improvements

- Add more NEPSE-listed companies.
- Daily Return Analysis.
- Correlation Heatmaps.
- Candlestick Charts.
- RSI (Relative Strength Index).
- MACD Indicator.
- Bollinger Bands.
- Interactive dashboards using Plotly.
- Machine Learning-based stock price prediction.

---

## 🙏 Acknowledgements

Special thanks to **Nepse Alpha** for providing publicly accessible historical NEPSE market data, making educational and analytical projects like this possible.

This repository is intended for educational and portfolio purposes only and is **not affiliated with or endorsed by Nepse Alpha or the Nepal Stock Exchange (NEPSE).**

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sumit Sah**

If you found this project helpful, consider giving the repository a ⭐ on GitHub.