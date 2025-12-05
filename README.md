# Advanced House Price Prediction 🏠

End-to-end Machine Learning project for predicting residential house prices using the **Kaggle House Prices Dataset**.

---

## Project Overview

This project demonstrates a complete ML workflow:

* **Exploratory Data Analysis (EDA)**: Missing values, outliers, categorical & numerical analysis
* **Feature Engineering**: Temporal features, handling rare categories, encoding categorical variables
* **Scaling & Transformation**: MinMaxScaler, log transform for skewed features
* **Feature Selection**: Lasso Regression to select important features and reduce dimensionality

---

## Dataset

* **Source:** Kaggle – House Prices: Advanced Regression Techniques
* **File Used:** `train.csv`
* **Features:** 81 variables including numeric, categorical, discrete, and continuous features

---

## Key Steps

1. **EDA & Visualization**

   * Analyzed numerical & categorical features
   * Studied relationship with `SalePrice`

2. **Missing Value Handling**

   * Categorical: Fill with `"Missing"`
   * Numerical: Median imputation + indicator variables for missingness

3. **Feature Engineering**

   * Age-based transformation of year features
   * Rare category grouping (<1%)
   * Ordered encoding of categorical variables
   * Log transform for skewed numeric features

4. **Feature Scaling**

   * MinMaxScaler applied to all features

5. **Feature Selection**

   * Lasso Regression to shrink unimportant features
   * Retained features with non-zero coefficients

---

## Libraries

* Python, Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn: MinMaxScaler, Lasso, SelectFromModel

---
