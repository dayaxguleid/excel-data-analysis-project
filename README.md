# 🚴 Bike Sales Data Analysis & Excel Dashboard

## 📌 Project Overview

This project analyzes customer demographic and behavioral data to identify key factors influencing bike purchases.

The project covers the complete data analysis workflow in Microsoft Excel, including data cleaning, feature engineering, PivotTable analysis, data visualization, and interactive dashboard development.

---

## 🧹 Data Cleaning & Preparation

The original dataset contained **1,026 customer records**.

The following data preparation steps were performed:

* **Duplicate Removal:** Identified and removed 26 duplicate records, resulting in **1,000 unique customer entries**.
* **Data Normalization:** Standardized categorical values for easier analysis and visualization.

  * `M` → `Married`
  * `S` → `Single`
  * `F` → `Female`
  * `M` → `Male`
* **Commute Distance:** Standardized `10+ Miles` to `More than 10 miles`.
* **Feature Engineering:** Created an `Age Bracket` column using nested `IF` logic:

  * **Adolescent:** Under 31
  * **Middle Age:** 31–54
  * **Old:** 55 and older

---

## 📊 Key Findings & Insights

### 1. Income vs. Bike Purchase Behavior

Bike buyers had higher average incomes than non-buyers across both genders.

* **Male buyers:** $60,124 average income
* **Female buyers:** $55,774 average income

This suggests that income may be an important factor associated with bike purchasing behavior.

### 2. Age Group and Purchase Behavior

The **Middle Age group (31–54)** had the highest purchase conversion rate:

* **54.6% conversion**
* **383 of 701** customers purchased a bike

Customers aged **55+** had a significantly lower conversion rate of **31.2%**.

### 3. Commute Distance and Purchases

Customers with shorter-to-moderate commute distances showed stronger purchasing behavior.

The highest conversion rate reached **58.6%** for customers commuting **2–5 miles**.

For customers commuting **more than 10 miles**, the conversion rate dropped to **29.7%**.

---

## 🛠️ Excel Tools & Techniques Used

### Data Cleaning

* Remove Duplicates
* Find & Replace
* Data normalization
* Data organization

### Excel Formulas

* Nested `IF` statements
* Conditional logic
* Feature engineering

### Data Analysis

* PivotTables
* Aggregation
* Demographic analysis
* Purchase behavior analysis

### Data Visualization

* Clustered column charts
* Line charts
* Conditional formatting
* Slicers
* Interactive dashboard

### Dashboard Features

* Region filtering
* Education filtering
* Marital Status filtering
* Interactive visualizations
* Dynamic dashboard layout

---
## 📊 Dashboard Preview

![Bike Sales Dashboard](bike-sales-dashboard.png)
## 📈 Project Outcome

The analysis demonstrates how Excel can be used to transform raw customer data into meaningful business insights.

The dashboard provides an interactive way to explore customer demographics and identify patterns associated with bike purchasing behavior.

---

## 🎯 Skills Demonstrated

Through this project, I demonstrated practical skills in:

* Data cleaning
* Data preparation
* Feature engineering
* Excel formulas
* PivotTables
* Data visualization
* Dashboard development
* Business-oriented data analysis
* Extracting actionable insights from data

---

## 🚀 Future Improvements

Future versions of this project could include:

* Recreating the analysis using SQL
* Building an interactive Power BI dashboard
* Performing deeper statistical analysis
* Automating parts of the data-cleaning workflow with Python

---

## 👨‍💻 About Me

I am a Computer Science student developing practical skills in **Data Analytics and Networking** through hands-on projects.

This project is part of my growing data analytics portfolio and demonstrates my ability to work with raw data, perform analysis, create visualizations, and communicate business insights.
