# 🏦 Loan Approval Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview

This project aims to predict whether a loan application will be **Approved or Rejected** using Machine Learning models.

The project follows a complete Data Science pipeline:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation
- Model Comparison

---

## 📊 Dataset Information

The dataset contains financial and demographic information of applicants:

- Income (annual)
- Loan amount
- Loan term
- CIBIL score
- Residential, Commercial & Luxury assets
- Bank asset value
- Education
- Self-employment status

📁 Dataset available in: `data/loan_approval_dataset.csv`

---

## 🔍 Exploratory Data Analysis

### Loan Status Distribution
![Loan Status](images/loan_status_distribution.png)

### Loan Status by Education
![Education](images/loan_status_by_education.png)

### Loan Status by Self Employment
![Self Employment](images/loan_status_by_self_employment.png)

### Correlation Heatmap
![Heatmap](images/correlation_heatmap.png)

---

## ⚙️ Models Used

### 🌳 Decision Tree Classifier
- Max Depth: 5
- Accuracy: **97.66%**

### 🌲 Random Forest Classifier
- Number of Trees: 100
- Accuracy: **96.60%**

---

## 📈 Model Performance

### Model Comparison
![Comparison](images/model_accuracy_comparison.png)

### Decision Tree Confusion Matrix
![DT](images/decision_tree_confusion_matrix.png)

### Random Forest Confusion Matrix
![RF](images/random_forest_confusion_matrix.png)

---

## 🧠 Key Insights

- **CIBIL score is the most important feature** influencing loan approval
- Income and loan amount also play significant roles
- Decision Tree slightly outperformed Random Forest in this dataset
- The dataset is well-balanced (Approved vs Rejected)

---

## 📁 Project Structure

loan-approval-prediction-ml/
│
├── data/
│   └── loan_approval_dataset.csv
│
├── images/
│   ├── loan_status_distribution.png
│   ├── loan_status_by_education.png
│   ├── loan_status_by_self_employment.png
│   ├── distribution_of_numerical_features.png
│   ├── correlation_heatmap.png
│   ├── decision_tree_confusion_matrix.png
│   ├── random_forest_confusion_matrix.png
│   ├── model_accuracy_comparison.png
│   ├── decision_tree_visualization.png
│   ├── cibil_score_by_loan_status_boxplot.png
│   ├── income_annum_by_loan_status_boxplot.png
│   ├── loan_amount_by_loan_status_boxplot.png
│   ├── residential_assets_value_by_loan_status_boxplot.png
│   ├── commercial_assets_value_by_loan_status_boxplot.png
│   ├── luxury_assets_value_by_loan_status_boxplot.png
│   ├── bank_asset_value_by_loan_status_boxplot.png
│   ├── decision_tree_feature_importance.png
│   └── random_forest_feature_importance.png
│
├── notebooks/
│   └── loan_approval_prediction.ipynb   ✅ (MOVE HERE)
│
├── requirements.txt   ❗ (add if missing)
├── README.md          ❗ (add if not yet)
├── .gitignore
└── LICENSE
