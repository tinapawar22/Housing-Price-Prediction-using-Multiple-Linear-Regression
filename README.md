# Housing-Price-Prediction-using-Multiple-Linear-Regression



This project predicts housing prices in Delhi using multiple linear regression. It identifies key factors like area, number of bedrooms, and parking availability to help a real estate company optimize property pricing and understand market drivers.

---

## 📌 Problem Statement

A real estate company in Delhi wants to:
- Identify which variables most influence housing prices.
- Build a regression model to predict house prices based on area, number of rooms, bathrooms, parking, etc.
- Evaluate how well these variables predict pricing and guide business decisions.

---

## 📊 Dataset

The dataset includes details about houses in Delhi with the following features:
- `area` (in sq. ft.)
- `bedrooms`
- `bathrooms`
- `parking`
- `furnishingstatus`
- `price` (target variable)

---

## 🚀 Project Workflow

### 1. Data Preprocessing
- Handled missing values
- Converted categorical variables using dummy encoding
- Checked for multicollinearity using Variance Inflation Factor (VIF)

### 2. Model Building
- Trained multiple linear regression using `statsmodels`
- Used backward elimination to remove insignificant variables

### 3. Model Evaluation
- Evaluated performance using R² and RMSE
- Residual analysis for model assumptions
- Interpreted coefficients to understand feature impact

---

## 📈 Results

- **Significant predictors**: `area`, `bedrooms`, `bathrooms`
- **Model Performance**:
  - High **Adjusted R²**
  - Low **RMSE**
- Provided business insights for pricing optimization

---

## 🛠️ Tech Stack

- Python 3
- Jupyter Notebook
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn, Statsmodels

---



