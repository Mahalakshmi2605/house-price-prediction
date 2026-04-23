# House Price Prediction — End-to-End ML Project

## Overview

This project builds a machine learning model to predict house prices based on various features such as quality, living area, basement size, and garage capacity.
It demonstrates a complete data science workflow from data cleaning to model optimization and evaluation.

---

## Objective

To predict the **SalePrice** of houses using structured housing data and improve model performance using advanced techniques.

---

## Dataset

* 1460 rows, 81 features
* Mix of numerical and categorical variables
* Target variable: **SalePrice**

---

## Workflow

### 1. Data Cleaning

* Handled missing values using:

  * Median (numerical features)
  * Meaningful labels (categorical features)
  * Dropping high-missing columns

### 2. Exploratory Data Analysis (EDA)

* Identified skewness in target variable
* Analyzed relationships using correlation and plots

### 3. Feature Engineering

* One-Hot Encoding for nominal variables
* Label Encoding for ordinal variables
* Removed redundant and low-impact features

### 4. Model Building

* **Linear Regression (Baseline)**
* **Random Forest (Improved Model)**

---

## Model Performance

| Model             | RMSE    |
| ----------------- | ------- |
| Linear Regression | ~52,000 |
| Random Forest     | ~29,000 |

 Achieved **~40% improvement** using Random Forest.

---

## Key Insights

* **OverallQual** (construction quality) is the most influential feature
* **GrLivArea** (living area) strongly impacts house prices
* Basement and garage features significantly contribute to value

---

## Why Random Forest Performed Better

Linear Regression assumes a linear relationship, which limits its ability to capture complex patterns.

Random Forest:

* Captures non-linear relationships
* Handles feature interactions
* Reduces overfitting using multiple trees

---

## Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## Future Improvements

* Try Gradient Boosting models (XGBoost, LightGBM)
* Perform advanced feature engineering
* Deploy model using Streamlit or Flask

---

## Contact

Open to feedback and collaboration.
