# saudi-retail-analytics-Project
Retail Analytics Dashboard using Excel, Power Query, ETL, and Business Intelligence

![Excel](https://img.shields.io/badge/Tool-Excel-green?style=for-the-badge)
![PowerQuery](https://img.shields.io/badge/Data%20Cleaning-Power%20Query-blue?style=for-the-badge)
![ETL](https://img.shields.io/badge/Process-ETL-orange?style=for-the-badge)
![BI](https://img.shields.io/badge/Business-Intelligence-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=for-the-badge)
![Dashboard](https://img.shields.io/badge/Type-Business%20Intelligence-orange?style=for-the-badge)
![Data Cleaning](https://img.shields.io/badge/Focus-Data%20Cleaning%20%26%20Transformation-red?style=for-the-badge)

---

# 📌 Project Overview

This project is a complete **retail analytics and business intelligence solution** built using **Excel, Power Query, Pivot Tables, and Interactive Dashboards**.

The dataset (`Saudi_Retail_Dataset`) was completely **self-created and intentionally designed to be messy**, including inconsistencies, logical errors, formatting issues, and calculation-based anomalies. The goal was to simulate a real-world raw dataset scenario and demonstrate advanced data preparation skills.

The project initially focused on demonstrating advanced **data cleaning and transformation skills using Power Query**. Using **Power Query in Excel**, The dataset was cleaned, transformed, and structured into a fully analytical model. After building the ETL and cleaning workflow, the project was extended into a full business analytics solution with KPI tracking, profitability analysis, customer segmentation, and sales performance dashboards.

---

# 📸 Project Screenshots

## Before Cleaning Transactions

## Before Cleaning Returns


---

## After Cleaning Transactions

## After Cleaning Returns


---

## Executive Sales Dashboard


---

## Profitability & Cost Analysis Dashboard


---

## 🧠 Core Objectives

- Demonstrate real-world advanced data cleaning & Data Transformation expertise
- Build an automated ETL workflow using Power Query
- Handle multi-file monthly transaction data
- Create a structured analytical data model
- Develop interactive Excel dashboards
- Generate actionable business insights from raw data

---

## 🧰 Tools & Technologies

- Microsoft Excel  
- Power Query (Data Cleaning & ETL)  
- Power Pivot (Data Modeling)  
- Pivot Tables  
- Pivot Charts  
- Data Visualization  

---

# 📂 Dataset Structure

## 🧾 Master Tables

### Customers.xlsx
Contains:
- Customer ID
- Customer Name
- Gender
- Age
- City
- Customer Segment
- Joining Date

📌 Records: **11,300+ Customers**

---

### Products.xlsx
Contains:
- Product ID
- Product Name
- Category
- Subcategory
- Base Price
- Standard Cost

📌 Records: **300+ Products**

---

### Stores.xlsx
Contains:
- Store ID
- Store Name
- City
- Region
- Store Size
- Opening Year
- Product Availability

📌 Records: **20 Retail Stores across Saudi Arabia**

---

## 🛒 Sales Transactions Folder

Folder-Based Monthly Transaction Files:

- October_2025.xlsx
- November_2025.xlsx
- December_2025.xlsx
- January_2026.xlsx
- February_2026.xlsx

Each workbook contains:
- Transactions Sheet
- Returns Sheet

📌 Total Transactions: **106,000+**
📌 Monthly Transactions: **~20,000 per file**

---

## 🔁 Returns Data

Each monthly file also contains returns data including:
- Return ID
- Transaction ID
- Return Date
- Return Reason
- Return Amount

📌 Average Returns per Month: **~1,000 records**

---

# ⚙️ Data Cleaning & Transformation (Power Query)

This project was originally designed as a **high-level data cleaning project**.

The raw dataset intentionally included:
- Inconsistent text formatting
- Extra spaces
- Mixed capitalization
- Incorrect region spellings
- Messy store names
- Inconsistent city names
- Date formatting issues
- Multi-source monthly files
- Logical calculation inconsistencies

### Cleaning & ETL Workflow:
- Combined monthly files using **Folder Connection**
- Applied automated transformations
- Standardized text formatting
- Fixed inconsistent naming conventions
- Corrected data types
- Cleaned returns data
- Removed formatting inconsistencies
- Created calculated business fields
- Built refreshable ETL workflow

📌 New monthly files can now be added directly into the folder and automatically processed after refresh.

---

# 🔗 Data Modeling

Relationships were created between:
- Transactions ↔ Customers
- Transactions ↔ Products
- Transactions ↔ Stores
- Transactions ↔ Returns

This enabled:
- Cross-table KPI calculations
- Dynamic filtering
- Advanced Pivot Analysis
- Interactive dashboards

---

# 📊 Dashboards Included

## 🟦 Executive Sales Dashboard

### Dashboard Focus:
Overall business performance monitoring.
Provides a high-level overview of business performance including revenue, profit, sales trends, category performance, store analysis, and customer segmentation.

### KPIs Included:
- Gross Sales
- Net Sales
- Net Revenue
- Total Profit
- Total Orders
- Total Quantity Sold
- Total Discount
- Total Returns
- Total Cost
- Return Rate %
- Discount Rate %
- Profit Margin %
- Average Order Value

### Visual Analysis Included:
- Monthly Sales Trend
- Sales by Category
- Top Performing Stores
- Customer Distribution by Segment
- Profit Contribution by Category

### Interactive Features:
- Region Filters
- Category Filters
- Segment Filters
- Year Filters
- Monthly Slicers

---

## 🟧 Profitability & Cost Analysis Dashboard

### Dashboard Focus:
Understanding profitability drivers and revenue leakage.
Focuses on identifying profit drivers, cost structure, discount impact, return impact, and revenue leakage across categories, stores, and customer segments.

### KPIs Included:
- Total Profit
- Profit Margin %
- Net Sales
- Total Cost
- Cost-to-Sales Ratio %

### Visual Analysis Included:
- Category Profit Breakdown
- Cost vs Sales Comparison
- Discount Impact on Profit
- Return Impact Analysis
- Discount vs Profit Relationship

### Key Objective:
Identify how discounts, costs, and returns affect profitability.

---

# 📈 Key Business Metrics

| Metric | Value |
|---|---|
| 💰 **Gross Sales** | 149.52M |
| 🧾 **Net Sales** | 132.88M |
| 📉 **Net Revenue** | 127.02M |
| 📊 **Total Profit** | 6.45M |
| 📦 **Total Orders** | 106,356 |
| **Total Quantity Sold** | 338,124 |
| **Total Discount** | 16.64M |
| **Total Returns** | 5.86M |
| **Total Cost** | 126.42M |
| 💸 **Profit Margin** | 4.86% |
| 🎯 **Discount Rate** | 12.52% |
| 🔁 **Return Rate** | 4.41% |
| **Average Order Value** | 1,249 SAR |

---

# 🔍 Key Insights

- Electronics is the strongest business category, generating the highest revenue and profit contribution.
- Home Appliances and Baby Products also contribute significantly to overall business performance.
- The business operates on a relatively low-margin retail model (~5% margin), making it highly sensitive to cost, discounting, and returns.
- Discounts and returns have a major impact on profitability.
- December 2025 recorded the highest monthly sales performance.
- February 2026 also showed strong business growth momentum.
- Retail and Occasional customers generate the majority of transactions.
- VIP customers contribute lower transaction volume but higher-value purchases.
- Cost-to-Sales ratio remains very high (~95%), indicating tight operational margins.
- Electronics and Home Appliances experience the highest return impact due to high sales volume.
- Some categories such as Grocery, Beauty, and Stationery show comparatively low contribution to revenue and profit.

---

## ⚠️ Business Challenges Identified

- High dependency on discount strategies
- Low overall profit margin
- Revenue leakage due to returns
- Uneven category performance distribution
- Cost structure pressure on profitability

---

## 🚀 Recommendations

- Optimize discount strategy to protect margins
- Reduce return rates through product quality and validation improvements
- Focus on high-performing categories (Electronics & Home Appliances)
- Improve VIP customer engagement and retention strategy
- Re-evaluate low-performing product categories

---

# ⚠️ Challenges Solved

- Multi-source file integration
- Folder-based automated ETL pipeline
- Large-scale data cleaning
- Inconsistent raw data handling
- Data modeling across multiple tables
- KPI calculation logic
- Revenue leakage analysis
- Dynamic dashboard reporting

---

# 🚀 Skills Demonstrated

## Data Cleaning & ETL
- Power Query
- Folder-based automation
- Data transformation
- Data standardization

## Data Analytics
- KPI Development
- Profitability Analysis
- Customer Segmentation
- Revenue Analysis
- Return & Discount Analysis

## Dashboard Development
- Pivot Tables
- Pivot Charts
- Interactive Slicers
- Executive Dashboard Design

## Business Intelligence
- Business Performance Tracking
- Profit Leakage Detection
- Trend Analysis
- Decision Support Reporting

---

# 📌 Project Status

✔ Dataset Creation  (Self-Designed & Intentionally Messy)
✔ Data Cleaning & ETL  (Power Query)
✔ Data Modeling  Completed
✔ Dashboard Development   Completed
✔ Business Analysis  
✔ Insight Generation  

---

# 👨‍💻 Author

**Created by:** Junaid Khan 

Excel | Power Query | Data Analytics | Business Intelligence

---

#  Final Note

This project was built as a self-learning initiative to simulate a real-world retail analytics environment and demonstrate complete end-to-end analytical workflow capabilities, from raw messy data to final business insights and dashboard reporting.

---

## ⭐ Support

If you find this project helpful, consider giving it a ⭐ and connecting on LinkedIn.

