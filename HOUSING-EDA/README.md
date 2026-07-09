# 🏠 Housing Prices - Exploratory Data Analysis (EDA)

## 📌 Overview

This project presents an **Exploratory Data Analysis (EDA)** of the **Ames Housing** dataset using Python. The objective is to understand the structure of the dataset, clean missing values, detect outliers, explore relationships between variables, and gain insights into factors affecting house sale prices.

---

## 📂 Dataset

**Dataset Name:** Ames Housing Training Dataset

**Source:** Ames Housing Dataset

The dataset contains information related to residential properties, including:

- Lot Area
- Lot Frontage
- House Style
- Overall Quality
- Year Built
- Living Area
- Garage Information
- Basement Information
- Exterior Features
- Sale Price
- And many other housing attributes

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Google Colab

---

## 📊 Analysis Performed

### 1. Data Loading

- Loaded the housing dataset into a Pandas DataFrame.
- Verified successful data import.

### 2. Dataset Inspection

- Examined dataset dimensions.
- Reviewed column names and data types.
- Identified missing values.

### 3. Missing Value Handling

- Replaced missing values in **LotFrontage** using the median.
- Filled missing values in **MasVnrType** using the most frequent category (mode).

### 4. Outlier Detection

- Visualized Sale Price distribution using boxplots.
- Detected outliers using the **Interquartile Range (IQR)** method.
- Identified extreme values using the **Z-Score** method.
- Compared the number of outliers detected by both techniques.

### 5. Data Visualization

Created visualizations including:

- Sale Price Distribution
- House Style Distribution
- Living Area vs Sale Price Scatter Plot

### 6. Correlation Analysis

- Selected numerical features.
- Generated a correlation matrix to understand relationships between variables.

---

## 📈 Key Insights

- The dataset contains several missing values that require preprocessing.
- Median and mode are effective techniques for handling missing numerical and categorical data.
- Both IQR and Z-Score methods help identify potential outliers.
- Larger living areas generally correspond to higher sale prices.
- Correlation analysis highlights features that are strongly associated with house prices.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Load and inspect large datasets.
- Handle missing values.
- Detect outliers using multiple methods.
- Visualize data distributions.
- Explore relationships between variables.
- Perform correlation analysis.
- Prepare data for machine learning.

---

## 🚀 Future Improvements

Possible enhancements include:

- Feature engineering
- One-Hot Encoding
- Label Encoding
- Feature Scaling
- Heatmap visualization
- Predictive modeling using Machine Learning
- Feature importance analysis

---

## 📚 Skills Demonstrated

- Data Loading
- Data Inspection
- Missing Value Handling
- Outlier Detection
- Data Visualization
- Correlation Analysis
- Exploratory Data Analysis (EDA)
- Data Preprocessing

---

## 📄 Dataset Credit

This project uses the **Ames Housing Training Dataset**.

**Original Dataset:**

https://raw.githubusercontent.com/hjhuney/Data/master/AmesHousing/train.csv

The dataset is publicly available and is used solely for educational and portfolio purposes. All credit belongs to the original dataset providers and maintainers.

---

## 📌 Conclusion

This project applies Exploratory Data Analysis techniques to the Ames Housing dataset. Through data cleaning, outlier detection, visualization, and correlation analysis, the project provides meaningful insights into housing characteristics and the factors influencing sale prices while strengthening practical data analysis skills using Python.