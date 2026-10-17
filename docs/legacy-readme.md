# Telco Customer Churn Analysis

## Project Overview
This project analyzes a **telecom customer churn dataset** to understand why customers leave the company.  
It includes data cleaning, exploratory data analysis (EDA), visualizations, and insights into factors affecting churn.

---

## Dataset
- Source: Kaggle ([Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn))  
- Rows: 7,043  
- Columns: 21  
- Stored in: `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`

---

## Objectives
- Explore patterns in customer churn.  
- Identify which features influence churn (e.g., contract type, payment method, internet service).  
- Visualize key trends and insights.

---

## Tools & Libraries
- Python 3  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## Project Structure
Project/
│
├─ data/ ← Dataset CSV
├─ notebook/ ← Jupyter notebook
├─ outputs/ ← Saved visualizations
└─ README.md ← This file

---

## Key Steps
1. Data cleaning and type conversions.  
2. Exploratory Data Analysis (EDA) with visualizations.  
3. Count plots and comparisons of churn by features like gender, contract type, payment method, and internet service.  
4. Saved all graphs in `outputs/` folder.

---

## Key Observations
- Customers with **month-to-month contracts** churn more.  
- **High monthly charges** are associated with higher churn.  
- Certain payment methods and internet services correlate with churn.  

---

## Visualizations

| Graph | Description |
|-------|-------------|
| `churn_count.png` | Count of churned vs retained customers |
| `churn_vs_contract.png` | Churn by contract type |
| `churn_vs_gender.png` | Churn by gender |
| `churn_vs_payment.png` | Churn by payment method |
| `churn_vs_internet.png` | Churn by internet service |

> All graphs are in the `outputs/` folder.

