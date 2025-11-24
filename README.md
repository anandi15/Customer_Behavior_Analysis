CUSTOMER SHOPPING BEHAVIOR ANALYSIS PROJECT README

1. PROJECT OVERVIEW
   
   This project analyzes customer shopping behavior using transactional data to understand spending patterns, purchase preferences, demographic influences, and subscription behavior. The workflow includes Python-based EDA, data cleaning, SQL analysis in MySQL Server, Power BI dashboard creation, and final reporting.

---

2. DATASET SUMMARY

* Rows: ~3,900
* Columns: 18
* Key Features:
  Age, gender, location, subscription status, purchase amount, product details, season, discount applied, promo code used, review rating, frequency of purchases, shipping type.
* Missing Values: Primarily in review rating column.
* Project Goal: Generate actionable business insights from customer behavior.

---

3. EXPLORATORY DATA ANALYSIS (PYTHON)
   Key steps performed using Python (Pandas, NumPy, Matplotlib/Seaborn):

a. Data Loading
Imported the dataset into Python using Pandas.

b. Initial Exploration
Checked structure (df.info), summary statistics (df.describe), and missing values.

c. Data Cleaning

* Imputed missing review ratings using category-wise median.
* Standardized column names.
* Removed redundant fields such as promo_code_used.

d. Feature Engineering

* Created age_group by binning age values.
* Converted purchase frequency text into numeric purchase_frequency_days.

e. Database Export
Loaded the cleaned dataset into MySQL Server for SQL-based analysis.

---

4. SQL ANALYSIS (MYSQL SERVER)
   SQL queries were executed to derive structured business insights.
   Major analyses include:

* Revenue comparison by gender
* Identifying discount users who spend above average
* Finding top-rated products
* Standard vs Express shipping purchase comparison
* Subscriber vs non-subscriber spending behavior
* Identifying discount-dependent products
* Customer segmentation (new, returning, loyal)
* Top products in each category
* Revenue contribution by age group
* Relationship between purchase frequency and subscription status

---

5. POWER BI DASHBOARD
   An interactive Power BI dashboard was created to visualize:

* Revenue trends
* Customer segments
* Product category performance
* Review rating patterns
* Discount usage behavior
* Subscriber distribution
* Geographic insights

The dashboard provides clear and actionable business intelligence.

---

6. FINAL REPORT AND PRESENTATION

* A structured analytical report summarizing key insights.
* A decision-focused presentation created using Gamma.
* Business recommendations include:

  * Improve loyalty programs
  * Optimize discount strategy
  * Target high-value age groups
  * Promote top-rated and high-selling products
  * Encourage more customers to subscribe

---

7. KEY BUSINESS INSIGHTS

* Loyal customers and subscribers contribute a large portion of revenue.
* Discount usage impacts purchase behavior but may affect margins.
* Express shipping users tend to spend more.
* Certain age groups drive higher revenue.
* Product categories vary significantly in rating and sales performance.

---

8. TECHNOLOGIES USED

* Python (Pandas)
* MySQL Server and MySQL Workbench
* Power BI
* Gamma for presentations
* Jupyter Notebook

---


