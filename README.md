# 🏦 Bank Loan Data Analysis Project

This project explores and analyzes a bank’s loan dataset to uncover patterns in **loan approval, default risks, customer behavior**, and **financial performance**.  
The analysis includes **Exploratory Data Analysis (EDA)**, visual insights, and **data-driven recommendations** to help the bank make smarter lending decisions.

---

## 📊 Project Overview

The goal of this project is to:
- Identify key factors influencing loan approval and default.
- Analyze customer demographics, loan amounts, and repayment trends.
- Derive actionable insights using visualizations and statistical summaries.
- Suggest business strategies for improved credit risk management.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**, **Plotly**
- **Scikit-learn** (for feature correlation and possible prediction)
- **Jupyter Notebook**

---

## 📁 Dataset Description

| Column Name           | Description |
|------------------------|-------------|
| `Loan_ID`              | Unique identifier for each loan |
| `Gender`               | Male/Female |
| `Married`              | Applicant’s marital status |
| `Dependents`           | Number of dependents |
| `Education`            | Applicant’s education level |
| `Self_Employed`        | Employment status |
| `ApplicantIncome`      | Income of the applicant |
| `CoapplicantIncome`    | Income of co-applicant |
| `LoanAmount`           | Loan amount requested |
| `Loan_Amount_Term`     | Duration of the loan (months) |
| `Credit_History`       | Credit history (1 = good, 0 = bad) |
| `Property_Area`        | Urban / Semi-Urban / Rural |
| `Loan_Status`          | Loan approved (Y/N) |

---

## 🔍 Exploratory Data Analysis (EDA)

### 1. Data Cleaning
- Handled missing values in `LoanAmount`, `Credit_History`, and `Self_Employed`.
- Standardized categorical values.
- Converted numerical data types for analysis.

### 2. Univariate Analysis
- Distribution of applicant income and loan amount.
- Loan approval ratio by gender, marital status, and property area.


---

## 💡 Key Insights

- **Credit history** is the strongest determinant of loan approval. Applicants with a good credit history have an approval rate above 80%.
- **Applicant income** positively correlates with loan approval but with diminishing returns above a certain threshold.
- **Self-employed individuals** face slightly lower approval rates, suggesting potential bias or risk-based restrictions.
- **Urban areas** show the highest loan approvals and average income.
- **Applicants with dependents** tend to request higher loans but have lower approval rates.

---

## 🧭 Recommendations

1. **Credit Scoring Priority:**  
   Give higher weight to credit history in the loan approval model.

2. **Targeted Financial Products:**  
   Offer special loan packages for **self-employed** applicants with strong income consistency.

3. **Income-based Risk Profiling:**  
   Introduce tiered loan limits to manage exposure among low-income applicants.

4. **Rural Loan Incentives:**  
   Provide rural applicants with lower-interest micro-loans to increase inclusion.

5. **Customer Education:**  
   Educate applicants on how to build and maintain good credit histories.

---



