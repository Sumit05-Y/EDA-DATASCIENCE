# 📧 Email Spam Detection - Exploratory Data Analysis (EDA)

An **Exploratory Data Analysis (EDA)** project on an SMS Spam Collection dataset. The objective of this project is to explore, clean, and preprocess the dataset before applying Machine Learning models for spam detection.

The project covers dataset exploration, missing value analysis, label encoding, and exporting a cleaned dataset that is ready for future Natural Language Processing (NLP) and Machine Learning tasks.

---

## 📌 Project Overview

Email and SMS spam detection is one of the most common text classification problems in Machine Learning. Before building a predictive model, understanding and preparing the dataset is an essential step.

In this project, the dataset is analyzed to:

- Understand the dataset structure
- Explore features and data types
- Check for missing values
- Convert categorical labels into numerical values
- Prepare the dataset for Machine Learning

---

## 📂 Dataset

The dataset consists of SMS messages categorized into:

| Category | Description |
|----------|-------------|
| Ham | Legitimate (Non-Spam) Message |
| Spam | Unwanted or Promotional Message |

### Features

- **Category** – Spam or Ham label
- **Message** – SMS text content

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The following EDA steps were performed:

- Imported required libraries
- Loaded the dataset
- Displayed sample records
- Checked dataset dimensions
- Examined data types
- Generated dataset information
- Checked for missing values
- Explored category distribution

---

## 🔄 Data Preprocessing

The preprocessing steps include:

- Verified that the dataset contains **no missing values**
- Encoded categorical labels into numerical values:
  - **Spam → 0**
  - **Ham → 1**
- Exported the cleaned dataset as:

```
Spam_clean.csv
```

The cleaned dataset is now suitable for Machine Learning and NLP workflows.

---

## 📁 Project Structure

```
EMAIL_SPAM-EDA/
│
├── data.csv
├── Spam_clean.csv
├── SPAMMAILEDA.ipynb
├── readme.md
```

---

## 📈 Output

After preprocessing, the dataset is:

- Cleaned
- Free from missing values
- Numerically encoded
- Ready for Machine Learning models such as:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest

---

## 🎯 Learning Outcomes

Through this project, I learned how to:

- Perform Exploratory Data Analysis (EDA)
- Inspect dataset structure
- Handle categorical variables
- Encode labels for Machine Learning
- Prepare text datasets for NLP tasks
- Export cleaned datasets for future use

---

## 🚀 Future Work

The cleaned dataset can be used to build a complete Spam Detection system using:

- Text Preprocessing
- CountVectorizer
- TF-IDF Vectorization
- Naive Bayes Classifier
- Logistic Regression
- Support Vector Machine (SVM)
- Model Evaluation and Performance Comparison

---

## 🙏 Dataset Credits

The dataset used in this project was obtained from the following open-source repository:

**KalyanM45 – Spam Email Detection**

Repository:
https://github.com/KalyanM45/Spam-Email-Detection

Dataset Source:
https://github.com/KalyanM45/Spam-Email-Detection/tree/main/data/dataset

Special thanks to **KalyanM45** for making the dataset publicly available for educational and research purposes.

> **Note:** This repository focuses on Exploratory Data Analysis (EDA) and data preprocessing. The analysis, preprocessing, notebook implementation, and documentation in this project were completed by **Sumit Sah**.

---

## 👨‍💻 Author

**Sumit Sah**

GitHub: https://github.com/Sumit05-Y

---

⭐ If you found this project helpful, feel free to star the repository.