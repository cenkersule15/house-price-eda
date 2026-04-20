# 🏠 House Price Prediction - EDA

This project performs an **Exploratory Data Analysis (EDA)** on the Kaggle House Prices dataset to understand the factors that influence house prices.

---

## 📌 Project Overview

The goal of this project is to explore and analyze the dataset before building any machine learning model.

We focus on:
- Understanding data structure
- Identifying missing values
- Exploring feature distributions
- Analyzing relationships with the target variable
- Creating new meaningful features

---

## 📊 Dataset

- Source: Kaggle - *House Prices: Advanced Regression Techniques*
- Rows: 1460  
- Columns: 81  
- Target variable: `SalePrice`

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Seaborn
- Matplotlib

---

## 🔍 Steps Performed

### 1. Data Loading & Overview
- Checked dataset shape and structure
- Inspected data types

### 2. Missing Values Analysis
- Identified columns with missing values
- Ranked features by missing count

### 3. Target Variable Analysis
- Analyzed `SalePrice` distribution
- Observed skewness and spread

### 4. Feature Types
- Separated:
  - Numerical features
  - Categorical features

### 5. Correlation Analysis
- Created correlation heatmap
- Identified strongest predictors of `SalePrice`

### 6. Categorical Analysis
- Compared categories vs SalePrice using boxplots

### 7. Feature Engineering
Created new features:
- `TotalSF` → Total square footage
- `HouseAge` → Age of the house
- `RemodAge` → Years since last renovation

---

## 📈 Key Insights

- `SalePrice` is **right-skewed**
- Strong predictors:
  - `OverallQual`
  - `GrLivArea`
  - `GarageCars`
  - `TotalSF`
- Missing values are concentrated in specific features
- Larger living areas and higher quality significantly increase price

---

## 🚀 Future Work

- Handle missing values with advanced techniques
- Encode categorical variables
- Apply machine learning models:
  - Linear Regression
  - Random Forest
  - XGBoost
- Evaluate performance using RMSE / RMSLE

---

## 👤 Author

**Cenker Sule**  
AI & Data Science Student

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!