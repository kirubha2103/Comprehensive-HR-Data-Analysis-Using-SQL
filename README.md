📊 Comprehensive HR Data Analysis Using MySQL
📁 Project Overview

This project focuses on performing **end-to-end data cleaning, transformation, and analysis** on an HR dataset using **MySQL**. The goal is to extract actionable insights related to employee performance, experience levels, attrition, and salary distribution across departments and countries.

---
 🎯 Objectives

* Clean and prepare raw HR data for analysis
* Handle missing values and remove duplicate records
* Create derived features such as *Experience Level* and *Salary Band*
* Perform exploratory data analysis (EDA) using SQL
* Generate business insights on hiring trends, salary patterns, and employee attrition

---

🛠️ Tools & Technologies

* **Database:** MySQL
* **Techniques:** Data Cleaning, Transformation, Feature Engineering, Window Functions, Aggregations
* **Key SQL Functions Used:** `CASE`, `RANK()`, `ROW_NUMBER()`, `PERCENT_RANK()`, `NTILE()`, `SUM()`, `AVG()`

---

🧹 Data Cleaning & Preparation

* Renamed tables and standardized column names
* Removed duplicates and handled missing values
* Split the *Location* column into *City* and *Country* using string functions
* Trimmed unwanted spaces and standardized text casing
* Verified data ranges for salary, experience, and performance ratings

---

🧠 Feature Engineering

* **Experience Level:** Categorized employees as *Junior*, *Mid-level*, or *Senior* based on years of experience.
* **Salary Band:** Grouped employees into *Low*, *Medium*, *High*, and *Executive* salary ranges.

---

📈 Data Analysis & Insights

* Department-wise employee count and average salary
* Experience level vs. average salary comparison
* Attrition rate by department
* Top 10 highest-paid employees
* Year-wise hiring trends
* Performance vs. salary relationship
* Salary percentile and quartile distribution

---

🏁 Key Outcomes

* Identified departments with the highest attrition and salary variance
* Revealed salary distribution across experience levels
* Highlighted high-performing employees and hiring growth trends
* Demonstrated strong SQL skills in data cleaning, transformation, and analysis

---

📂 Project Structure

```
📁 HR_Data_Analysis_SQL
│
├── hr_data.sql                # Main SQL script file
├── hr_dataset.csv             # Dataset used for analysis
├── README.md                  # Project documentation
```

---

🚀 Future Enhancements

* Integrate Power BI or Tableau for visualization
* Automate data refresh using ETL pipelines
* Build a dashboard for HR metrics and KPIs

---
 Performed data cleaning, transformation, and analysis on an HR dataset using MySQL. Handled missing values, removed duplicates, created experience and salary bands, and used SQL window functions to analyze performance, attrition, and salary trends across departments and countries.
