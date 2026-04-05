# 📊 Unemployment Rate Prediction Project

## 🚀 Project Overview
This project focuses on predicting unemployment rates using Machine Learning techniques. It includes complete data analysis, preprocessing, and model building.

---

## 🎯 Objectives
- Perform advanced Exploratory Data Analysis (EDA)
- Handle missing values, duplicates, and outliers
- Engineer meaningful features
- Build and optimize machine learning models
- Evaluate model performance

---

## 📂 Dataset
- Source: Kaggle
- Records: 500+ rows
- Features: 7+ columns

---

## 🔍 Key Steps

### 1. Data Cleaning
- Handled missing values using mode imputation
- Removed duplicate records
- Outlier removal using IQR method

### 2. Feature Engineering
- Extracted time-based features (year, month)
- Applied cyclical encoding
- One-hot encoding for categorical variables

### 3. EDA Insights
- Regional disparities in unemployment
- Urban vs Rural differences
- Weak correlations → non-linear modeling required

### 4. Model Building
- Random Forest
- XGBoost

### 5. Model Optimization
- Hyperparameter tuning using GridSearchCV

---

## 📊 Results

| Model          | R² Score |
|---------------|---------|
| Random Forest | ~0.80+   |
| XGBoost       | ~0.80+  |

---

## 📈 Key Insights
- Unemployment varies significantly across regions
- Seasonal patterns affect unemployment rates
- Feature engineering improved model performance

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 💡 Future Improvements
- Deploy using Streamlit
- Add more datasets
- Use Deep Learning models

---

## 👨‍💻 Author
Aniket Jadhao
