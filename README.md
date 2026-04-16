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
- Main file used: `train.csv`
- Rows: 1460  
- Columns: 81  

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
- `TotalBathrooms` → Combined bathroom metric

---

## 📈 Key Insights

- `SalePrice` is **right-skewed**
- Strong predictors:
  - `OverallQual`
  - `GrLivArea`
  - `TotalSF`
- Several features contain **missing values**
- Feature engineering improves data representation

---

## 📊 Example Visualization

- Correlation heatmap
- Distribution plots
- Boxplots for categorical variables

---

## 🚀 Future Work

- Handle missing values properly
- Encode categorical variables
- Apply machine learning models
- Evaluate model performance

---

## 👤 Author

**Cenker Sule**  
AI & Data Science Student

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!