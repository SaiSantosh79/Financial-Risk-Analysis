# 📊 Financial Risk Assessment – Data Analysis Project

## 📌 Problem Statement
Financial institutions face challenges in identifying customers who are likely to default or pose higher financial risk.  
Manual evaluation is time-consuming and prone to bias, while poor risk assessment can lead to loan losses and reduced profitability.

**Objective:**  
To analyze customer financial and demographic data to identify risk patterns and classify individuals into **Low, Medium, and High Risk** categories for better decision-making.

---

## 📂 Dataset Overview
The dataset represents simulated real-world financial customer data and includes:
- Demographic information (Age)
- Financial indicators (Income, Assets Value, Loan Amount, Credit Score)
- Existing liabilities and balances
- Target variable: **Risk Category (Low / Medium / High)**

The dataset intentionally contains:
- Missing values  
- Outliers  
- Mixed data distributions  

to reflect real business scenarios.

---

## 🔍 Analysis Performed

### 1. Data Understanding
- Reviewed dataset structure using `.head()`, `.info()`, and `.describe()`
- Identified numerical and categorical variables

### 2. Data Cleaning
- Handled **12.4% missing values** using imputation techniques
- Corrected data types and formatting issues
- Treated **3.8% extreme outliers** in financial variables

### 3. Exploratory Data Analysis (EDA)
- Analyzed income, credit score, and loan amount distributions
- Studied correlations between financial attributes
- Compared risk categories across income and credit score ranges

### 4. Insights Extraction
- High-risk customers generally have lower credit scores and higher loan-to-income ratios
- Strong positive correlation observed between income and asset value
- Credit score shows a significant inverse relationship with financial risk

---

## 💼 Business Solution
Based on the analysis, the following business solutions are recommended:

- **Risk-Based Customer Segmentation**  
  Categorize applicants into Low, Medium, and High risk groups before loan approval.

- **Improved Loan Approval Strategy**  
  Use combined financial indicators instead of a single metric for decision-making.

- **Loss Reduction**  
  Early identification of high-risk customers reduces default rates.

- **Data-Driven Decisions**  
  Enables financial teams to move from intuition-based to insight-driven evaluation.

---

## 📈 Key Insights
- Customers with **low credit scores and high loan amounts** are more likely to fall into the High-Risk category.
- **Income and asset value** show strong positive correlation, indicating financial stability.
- Cleaning missing values and outliers significantly improves data quality and analysis accuracy.

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib / Seaborn** – Data visualization
- **Jupyter Notebook** – Analysis environment

---

## ✅ Conclusion
This project demonstrates how financial data can be transformed into actionable insights for risk assessment.  
The analysis supports better loan approval strategies, minimizes financial losses, and highlights the importance of data-driven decision-making in the finance domain.

This project showcases my skills in:
- Data Cleaning & Exploratory Data Analysis  
- Business Problem Understanding  
- Translating data insights into business value  

---

