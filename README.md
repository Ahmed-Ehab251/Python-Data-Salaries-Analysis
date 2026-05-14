# Salaries Analysis | Python (EDA)

## Overview
This project performs Exploratory Data Analysis (EDA) on an employee salaries dataset using Python.  
The goal is to extract insights about salaries, job titles, overtime pay, and employee compensation trends.

---

## Tools Used
- Python
- Pandas

---

## Dataset
The dataset contains employee salary information including:
- Employee Name
- Job Title
- Base Pay
- Overtime Pay
- Benefits
- Total Compensation
- Year

---

## Data Exploration Steps

### 1. Data Loading
- Imported dataset using Pandas
- Checked structure using `.head()` and `.info()`

---

### 2. Basic Statistics
- Calculated average BasePay
- Identified highest and lowest TotalPayBenefits

---

### 3. Job Title Analysis
- Found number of unique job titles
- Identified most common job roles
- Counted how many job titles appear only once in 2013
- Analyzed job titles containing the word "Chief"

---

### 4. Employee Salary Analysis
- Identified highest paid employee
- Identified lowest paid employee
- Extracted salary details for specific employees

---

### 5. Yearly Analysis
- Calculated average BasePay per year (2011–2014)
- Observed salary trends over time

---

### 6. Advanced Analysis
- Created new feature: Job Title length
- Analyzed correlation between Job Title length and Total Pay Benefits

---

## Key Insights
- Average BasePay is approximately 66,000
- Highest compensation exceeds 560,000
- Most employees fall under a few dominant job titles
- 202 job titles appeared only once in 2013
- Weak negative correlation between job title length and salary
- Salary distribution varies significantly across job roles and years

---

## Skills Demonstrated
- Data Cleaning and Exploration
- Pandas Data Manipulation
- GroupBy and Aggregation
- Filtering and Conditional Analysis
- Feature Engineering (Title Length)
- Correlation Analysis

---

## Conclusion
This project demonstrates how Python can be used to explore and analyze large-scale employee salary data to extract meaningful business insights.
