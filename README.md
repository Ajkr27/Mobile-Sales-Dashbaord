
# 📊 Mobile Sales Analytics Project

**Tech Stack:** SQL | Excel | Power BI (DAX) | Python (Pandas, Seaborn)

## 🔍 Overview

This project analyzes mobile sales data to uncover key business insights such as top-performing brands, revenue-driving cities, and customer behavior patterns. The goal was to build an end-to-end analytics pipeline using SQL for querying, Power BI for interactive dashboards, and Python for deep exploratory analysis.

---

## 🗂️ Dataset

The dataset contains 3,800+ records with the following columns:
- `Order_ID`, `Order_Date`, `Delivery_Date`
- `Customer_ID`, `City`, `Region`, `Gender`, `Age_Group`
- `Product_Name`, `Category`, `Brand`
- `Price`, `Quantity`, `Discount`, `Sales_Channel`
- `Cost_Price`, `Rating`, `Status`

---

## 🛠️ Tools & Technologies

- **SQL (MySQL):** For data extraction, transformation, and querying business KPIs  
- **Excel:** Used for initial cleaning and understanding of raw data  
- **Power BI:** Built a dynamic dashboard with custom DAX measures:
  - MTD, YTD, QTD
  - Same Period Last Year (SPLY)
  - Custom Calendar and filters  
- **Python (Pandas, Seaborn):**
  - Exploratory Data Analysis (EDA)
  - Visualization of revenue distribution, product trends, and age-based preferences

---

## 📌 Key Insights & Features

- 📈 Identified **top 5 brands by total quantity sold**
- 🌆 Revealed **city-wise revenue trends** and **gender-based purchase patterns**
- 🔁 Segmented **repeat customers** and calculated **AOV (Average Order Value)**
- 🔄 Monitored **return rates** and **discount performance**
- 📊 Dashboard with slicers for **brand, city, gender, and category**

---

## 🧠 SQL Highlights

✅ 17+ queries including:
- Brand-wise performance  
- Monthly sales trend  
- Repeat customer detection  
- Sales by age group & region  
- Day-of-week order frequency  
