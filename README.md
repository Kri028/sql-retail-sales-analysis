# sql-retail-sales-analysis
SQL project analyzing retail sales data, including data cleaning, exploration, and business insights using MySQL queries.

# SQL Retail Sales Analysis 📊

## 📌 Project Overview
This project analyzes **retail sales data** using SQL (MySQL 8.0). The dataset includes transactions, customer details, product categories, and sales amounts. The goal is to clean, explore, and extract meaningful business insights.  

## 🛠️ Technologies Used
- **SQL (MySQL 8.0)**
- **Window Functions (`RANK()`, `AVG()`, `SUM()`)**
- **CTEs (`WITH` statements)**
- **Data Cleaning & Aggregations**

## 🔍 Key Insights & Queries  
✅ **Data Cleaning:** Removed NULL values and ensured correct date formats.  
✅ **Exploration:** Identified unique customers, sales trends, and product performance.  
✅ **Business Analysis:**  
- 🔹 Best-selling month in each year  
- 🔹 Top 5 customers based on total sales  
- 🔹 Sales trends by category and gender  
- 🔹 Sales shift analysis (Morning, Afternoon, Evening)  

## 📂 SQL Queries
- **Q1**: Retrieve all sales on a specific date (`2022-11-05`)  
- **Q2**: Filter sales for Clothing category in November 2022  
- **Q3**: Calculate total sales (`SUM(total_sale)`) for each category  
- **Q4**: Find the average age of customers purchasing Beauty products  
- **Q5**: Identify transactions where total sales exceed 1000  
- **Q6**: Count transactions per gender & category  
- **Q7**: Find the best-selling month in each year using `RANK()`  
- **Q8**: Find top 5 customers based on total sales  
- **Q9**: Count unique customers per category  
- **Q10**: Categorize sales by shift (Morning, Afternoon, Evening)  

## 🚀 How to Use  
1. **Clone the repository:**  
   ```bash
   git clone https://github.com/YOUR-USERNAME/sql-retail-sales-analysis.git
