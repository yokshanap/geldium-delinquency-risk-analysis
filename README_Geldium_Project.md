
# 🧠 Geldium Delinquency Risk Analysis Project

This project focuses on understanding and predicting **loan delinquency risk** using real-world-style financial data from Geldium. It includes complete **Exploratory Data Analysis (EDA)**, data cleaning, and a basic **logistic regression model** to predict customer delinquency.

---

## 📌 Objective
Help Geldium identify **early warning signs** of customers who may default on their loans, using historical financial and behavioral data.

---

## 📁 Dataset Overview
The dataset includes:
- Customer demographics and income
- Credit score and credit utilization
- Loan balances and debt ratios
- Payment history over 6 months
- Target column: `Delinquent_Account` (0 = No, 1 = Yes)

---

## 🔍 Steps Performed

### 1. **Data Cleaning & Preprocessing**
- Handled missing values using imputation (median for income, mean for credit utilization)
- Removed inconsistencies like utilization > 100%
  
### 2. **Exploratory Data Analysis (EDA)**
- Identified key risk indicators: high credit utilization, missed payments, and high debt-to-income ratio
- Used seaborn/matplotlib to visualize relationships

### 3. **Modeling**
- Applied Logistic Regression to predict delinquency
- Evaluated using confusion matrix and classification report

---

## 📊 Key Risk Indicators Identified
- High Credit Utilization (>90%)
- High Missed Payments in last 6 months
- High Debt-to-Income Ratio
- Low or missing income values
- Unemployment status

---

## 🤖 Tools Used
- Python, Pandas, NumPy
- Seaborn & Matplotlib
- Scikit-learn (LogisticRegression, train_test_split)

---

## 📌 Future Work
- Try other ML models (Random Forest, XGBoost)
- Feature engineering: combine payment history into a score
- Address class imbalance using SMOTE or similar techniques

---

## 📁 File Included
- `geldium.ipynb`: Full EDA + model notebook

---

## 💡 Author
*This project was completed as part of a hands-on simulation to develop real-world data analytics skills.*
