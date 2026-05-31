# Vrinda Store Annual Sales Analysis (2022)

## 📌 Project Overview
This project presents an end-to-end Data Analytics workflow using Microsoft Excel to analyze the annual sales performance of **Vrinda Store** for the year 2022. The objective was to transform raw transactional data into meaningful business insights, enabling the store to understand its customer demographics, regional demand, and preferred retail channels to drive growth in 2023.

---

## 🎯 Business Problem Statement
Vrinda Store wants to create an annual sales report for 2022 to better understand its customers, optimize sales channels, and design a targeted marketing roadmap for the upcoming fiscal year.

---

## 🛠️ Data Analytics Workflow & Technical Execution

### 1. Data Cleaning
* Handled messy records in the `Gender` column by regularizing shorthand notations (e.g., converting "M" to "Men" and "W"/"w" to "Women").
* Inspected numeric formatting inconsistencies across columns like `Order ID`, `Customer ID`, and `Qty`.
* Scrubbed the dataset to verify that no structural null values or outliers corrupted the calculations.

### 2. Data Processing
* **Age Group Segmentation:** Created a nested conditional logic field using `IF` statements to bin individual ages into strategic customer segments:
  * `Senior` ($\ge$ 50)
  * `Adult` (30–49)
  * `Teenager` (< 30)
* **Time Intelligence:** Extracted short-hand month string characters (`Jan`, `Feb`, etc.) from transactional date stamps using the Excel `TEXT(Date, "mmm")` function to facilitate time-series analysis.

### 3. Data Analysis & Modeling
* Built multiple distinct **Pivot Tables** across back-end staging tabs to isolate operations from presentation layers.
* Calculated key matrix statistics mapping total sales revenue and transaction volumes concurrently.

### 4. Interactive Dashboard Presentation
* Designed a unified dynamic presentation interface featuring linked dynamic **Pivot Charts**.
* Configured advanced **Slicers** (Month, Channel, and Product Category) with cross-connected *Report Connections* to enable multi-dimensional filtering across all dashboard widgets simultaneously.

---

## 📈 Dashboard Preview
![Vrinda Store Dashboard](vrinda_dashboard.png)

---

## 💡 Key Business Insights Discovered
* **Top Sales Driver:** **Women** are the primary drivers of business value, contributing approximately **65%** of overall revenue.
* **Core Demographics:** The **Adult age tier (30–49)** represents the most valuable target group, commanding nearly **35%** of purchase volume.
* **Geographical Dominance:** **Maharashtra, Karnataka, and Uttar Pradesh** emerged as the top 3 revenue-generating states.
* **Channel Distribution:** Online e-commerce ecosystems (**Amazon, Flipkart, and Myntra**) heavily dominate orders, accounting for roughly **80%** of total distribution shares.

---

## 🚀 Final Strategic Recommendations for 2023
To optimize marketing budgets and scale total store revenue, Vrinda Store should prioritize a laser-focused campaign targeting **Adult Women (aged 30-49)** living in **Maharashtra, Karnataka, and Uttar Pradesh**. Utilizing targeted discount coupons and ads specifically on **Amazon, Flipkart, and Myntra** during peak buying cycles will offer the highest return on investment.

---

## 📁 How to Replicate and Use the Project
1. Clone or download this repository to access the `.xlsx` file.
2. Open the file via Microsoft Excel Desktop App.
3. Navigate directly to the first tab (`Vrinda Store Report`) to interactively filter trends using the slicers.
