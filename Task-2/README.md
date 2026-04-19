# 📊 Loan Default Prediction Project

This project predicts whether a loan applicant will default using machine learning models like Logistic Regression and Decision Tree.

---

## 🚀 Objective
To build a machine learning model that predicts loan default based on financial and personal attributes such as income, credit score, and debt-to-income ratio.

---

## 📁 Dataset
The dataset contains applicant information such as:
- Income
- Credit Score
- Loan Amount
- Employment Status
- Debt-to-Income Ratio
- Default (Target variable)

---

## 🧹 Data Preprocessing
- Removed unnecessary columns (e.g., LoanID)
- Handled missing values:
  - Numeric → Mean
  - Categorical → Mode
- Converted categorical variables using One-Hot Encoding
- Scaled features using StandardScaler (for Logistic Regression)

---

## 📊 Exploratory Data Analysis (EDA)
- Distribution of income
- Relationship between credit score and default
- Debt-to-income ratio analysis
- Correlation heatmap of features

---

## 🤖 Models Used
- Logistic Regression
- Decision Tree Classifier

---

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix

---

## 🏆 Results
- Logistic Regression performs better after feature scaling
- Decision Tree helps identify important features

---

## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

---

## 📌 Key Learnings
- Importance of feature scaling in Logistic Regression
- Handling categorical variables correctly
- Model comparison between linear and tree-based models

---

