# Loan Insights — SQL Data Cleaning, Customer Segmentation & Approval Analysis

This project analyzes loan application data for **FinTrust Bank**, focusing on customer risk profiles, loan approval patterns, and data quality issues.  
The goal is to clean the dataset, engineer useful features, and generate insights that support better lending decisions.

This project was completed as part of a **DataCamp Data Engineer Practical Exam**.

---

## 🔍 Business Problem

FinTrust Bank wants to improve its loan approval process by understanding:

- Which customer groups are most likely to default  
- Which loan types have the highest approval rates  
- How income, credit score, and employment status affect decisions  
- Where data quality issues may impact risk assessment  

The dataset contains missing values, inconsistent categories, and mixed data types that must be cleaned before analysis.

---

## 🛠️ Skills Used

- SQL Data Cleaning  
- Data Engineering Concepts  
- COALESCE, CASE, NULLIF  
- Aggregations (AVG, COUNT, SUM)  
- Customer Segmentation  
- Risk Profiling  
- JOIN operations  
- Feature Extraction  

---

## 📂 Project Tasks

### **Task 1 — Identify Missing Values**
Counted missing values across key fields such as:

- income  
- credit_score  
- employment_status  
- loan_amount  
- loan_type  

This establishes the baseline data quality.

---

### **Task 2 — Clean the Loan Dataset**
Applied cleaning rules:

- Missing employment_status → `"Unknown"`  
- Missing income → median income  
- Missing credit_score → median credit score  
- Missing loan_type → `"Other"`  
- Missing loan_amount → average loan amount  
- Standardized text fields (uppercasing, trimming spaces)  

---

### **Task 3 — Customer Risk Segmentation**
Created risk groups based on:

- credit_score  
- income  
- loan_amount  
- approval_status  

Segments included:

- **Low Risk**  
- **Medium Risk**  
- **High Risk**  

---

### **Task 4 — Loan Approval Insights**
Analyzed:

- Approval rate by loan_type  
- Approval rate by employment_status  
- Approval rate by risk group  
- Average loan amount by approval status  

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `loan_insights.pdf` | Original DataCamp practical exam submission |
| `sql/task1_missing_values.sql` | SQL for Task 1 |
| `sql/task2_clean_data.sql` | SQL for Task 2 |
| `sql/task3_risk_segmentation.sql` | SQL for Task 3 |
| `sql/task4_approval_insights.sql` | SQL for Task 4 |

---

## 🧠 Key Insights

- High‑risk customers had significantly lower approval rates.  
- Employment status strongly influenced approval decisions.  
- Certain loan types had consistently higher approval rates.  
- Cleaning and standardizing the dataset improved segmentation accuracy.  

---

## 👤 Author

**Bala Akhil Rajdeep Battula**  
Data & Technology Professional → Automotive Technology (WDTC Fall 2026)
