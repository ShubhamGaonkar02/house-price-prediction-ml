# 🏠 House Price Prediction ML Project

## 📌 Overview
This project aims to predict house prices using Machine Learning techniques based on various features such as area, quality, number of rooms, and more.

The project includes complete steps from data preprocessing and feature engineering to model training and evaluation.

---

## 📊 Dataset
- Dataset similar to Ames Housing Dataset
- Contains **1460+ rows and 80+ features**
- Includes both **numerical and categorical variables**

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 🔍 Project Workflow

### 1. Data Preprocessing
- Handled missing values:
  - Dropped columns with >40% missing values
  - Filled categorical values with `"None"`
  - Filled numerical values with median
- Removed outliers

---

### 2. Feature Engineering
- Created new features:
  - Total Square Footage
  - Total Bathrooms
  - House Age
- Label Encoding for categorical variables

---

### 3. Exploratory Data Analysis (EDA)
- Distribution plots of target variable (SalePrice)
- Log transformation applied
- Correlation analysis
- Heatmaps and feature importance visualization

---

## 🤖 Models Used

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

---

## 📈 Model Performance

| Model               | RMSE     | R² Score |
|--------------------|----------|----------|
| XGBoost            | 0.1199   | **0.9147** |
| Linear Regression  | 0.1268   | 0.9046 |
| Random Forest      | 0.1426   | 0.8793 |

✅ **Best Model: XGBoost**

---

## 📊 Results & Insights
- XGBoost achieved the highest accuracy (R² ≈ 0.91)
- Key important features:
  - Overall Quality
  - Total Square Footage
  - Garage Cars
  - Living Area

---

## 📉 Visualizations
- Sale Price Distribution (Original vs Log Transformed)
- Missing Values Analysis
- Feature Correlation Heatmap
- Model Comparison Graph
- Residual Plots

---


