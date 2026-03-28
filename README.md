Dưới đây là phần **README description** chuyên nghiệp, ngắn gọn nhưng đầy đủ để bạn dùng cho project này (có thể paste trực tiếp vào GitHub):

---

# 📊 Loan Risk Prediction & Data Analysis

## 📌 Overview

This project focuses on analyzing loan data and building machine learning models to predict financial risk, specifically **customer bankruptcy status**. The workflow includes data preprocessing, feature engineering, exploratory data analysis (EDA), and model training with hyperparameter tuning.

## ⚙️ Key Features

* 📥 Load and process dataset from Google Colab upload
* 🧹 Data cleaning:

  * Handle missing values
  * Remove duplicates
  * Fix incorrect values (e.g., Credit Score normalization)
* 🔄 Feature engineering:

  * Credit Score categorization (FICO-based)
  * Encoding categorical variables (One-hot & Label Encoding)
  * Transform skewed data (log transformation)
* 📊 Data visualization:

  * Distribution plots
  * Pairplots & heatmaps
  * Feature importance analysis
* 🤖 Machine Learning models:

  * Decision Tree
  * Random Forest
  * Logistic Regression
  * K-Nearest Neighbors (KNN)
* 🔍 Hyperparameter tuning using `RandomizedSearchCV`
* 📈 Model evaluation:

  * Accuracy
  * Confusion Matrix
  * Classification Report
  * ROC Curve & AUC score

## 🧠 Workflow

1. Data Loading & Inspection
2. Data Cleaning & Missing Value Handling
3. Feature Engineering & Encoding
4. Exploratory Data Analysis (EDA)
5. Model Training & Tuning
6. Model Evaluation & Selection

## 📦 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn

## 🎯 Objective

The main goal is to build a predictive model that helps identify customers at risk of bankruptcy, supporting better decision-making in financial services.

## 📊 Output

* Best model selected based on AUC score
* Performance metrics comparison across models
* Feature importance visualization
* Correlation analysis

## 🚀 How to Run

```bash
1. Upload dataset in Google Colab
2. Run all cells step-by-step
3. View results and visualizations
```

## 📌 Notes

* Dataset requires preprocessing before training
* Some features are heavily engineered to improve model performance
* Logistic Regression and KNN require feature scaling

---

