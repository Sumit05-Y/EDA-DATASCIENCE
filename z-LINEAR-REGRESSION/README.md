# 📈 Linear Regression

This folder contains multiple **Linear Regression** projects built using different real-world datasets. Each notebook follows a complete machine learning workflow—from data preprocessing and feature engineering to model training, evaluation, and prediction.

The purpose of this collection is to strengthen the understanding of regression techniques by applying **Linear Regression** across datasets from different domains, including **housing** and **financial stock market data**.

---

# 📌 Objectives

The primary goals of these projects are to:

- Understand the fundamentals of Linear Regression
- Build regression models using real-world datasets
- Practice data preprocessing and feature engineering
- Evaluate model performance using regression metrics
- Compare model performance across different datasets
- Learn how Linear Regression can be applied to both housing and stock price prediction problems

---

# 🛠 Machine Learning Workflow

Each notebook follows a similar workflow.

## 1. Data Loading

- Import dataset using Pandas
- Explore dataset structure
- Understand features and target variable

---

## 2. Data Preprocessing

- Handle missing values
- Remove duplicate records
- Convert data types where necessary
- Select relevant features

---

## 3. Exploratory Data Analysis (EDA)

- Analyze feature distributions
- Study relationships between variables
- Visualize trends and correlations
- Detect potential outliers

---

## 4. Feature Engineering

Depending on the dataset, this may include:

- Creating moving average features (for stock datasets)
- Encoding categorical variables (when required)
- Removing unnecessary columns
- Selecting important features

---

## 5. Feature Scaling

Numerical features are standardized using **StandardScaler** where appropriate to improve model performance.

---

## 6. Train-Test Split

The dataset is divided into training and testing sets to evaluate how well the model generalizes to unseen data.

---

## 7. Model Training

A **Linear Regression** model is trained to learn the relationship between input features and a continuous target variable.

Example prediction tasks include:

- 🏠 House Price Prediction
- 📈 NABIL Stock Closing Price Prediction
- 📊 NLIC Stock Closing Price Prediction

---

## 8. Model Evaluation

Model performance is evaluated using common regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score (Coefficient of Determination)

These metrics help measure prediction accuracy and overall model performance.

---

# 📂 Current Projects

| Notebook | Dataset | Prediction Task | Status |
|-----------|---------|-----------------|--------|
| **HOUSING(Linear).ipynb** | Ames Housing Dataset | House Price Prediction | ✅ Completed |
| **Nabil(LINEAR).ipynb** | NABIL Stock Dataset | Next-Day Stock Closing Price Prediction | ✅ Completed |
| **Nlic(LINEAR).ipynb** | NLIC Stock Dataset | Next-Day Stock Closing Price Prediction | ✅ Completed |

More regression projects will be added over time.

---

# 📁 Project Structure

```text
z-LINEAR-REGRESSION/
│
├── README.md
├── HOUSING(Linear).ipynb
├── Nabil(LINEAR).ipynb
├── Nlic(LINEAR).ipynb
└── Future Linear Regression Projects
```

---

# 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📚 Concepts Practiced

Through these projects, the following concepts are explored:

- Linear Regression
- Regression Analysis
- Predictive Modeling
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Train-Test Split
- Model Evaluation
- Stock Price Prediction
- House Price Prediction

---

# 🚀 Future Work

This collection will continue to grow with additional Linear Regression projects using diverse real-world datasets. Planned additions include datasets from domains such as:

- 💰 Finance
- 🏥 Healthcare
- 🛒 Retail
- 🌾 Agriculture
- 🌦 Weather & Climate
- 🏭 Manufacturing

Adding more projects will provide opportunities to compare Linear Regression performance across different regression problems while strengthening practical machine learning skills.