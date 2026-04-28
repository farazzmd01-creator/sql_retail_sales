# Retail Sales Analysis (SQL Project)

## Overview
This project focuses on analyzing a retail sales dataset using SQL to extract meaningful business insights. The goal is to understand customer behavior, sales trends, and product performance.

## Tools Used
- MySQL

## Dataset Details
The dataset contains transactional-level data including:
- Customer demographics (age, gender)
- Product categories
- Sales amount and quantity
- Date and time of transactions

---

## Business Questions Solved

1. Retrieve all sales made on a specific date  
2. Identify high-quantity clothing sales in a given month  
3. Calculate total sales and number of transactions per category  
4. Find average age of customers purchasing from a category  
5. Identify transactions with high sales value  
6. Analyze transactions based on gender and category  
7. Determine best-performing months by average sales  
8. Identify top 5 customers based on total spending  
9. Count unique customers per category  
10. Categorize sales based on time of day (Morning, Afternoon, Evening)

---

## Key Insights

- Certain product categories contribute significantly higher revenue than others  
- High-value transactions (₹1000+) form an important segment of total sales  
- Customer purchasing patterns vary across gender and product categories  
- Specific months show higher average sales, indicating seasonal trends  
- A small group of customers contributes a large portion of total revenue  
- Sales activity varies by time of day, with clear peaks in certain shifts  

---

## Advanced Analysis

- Used **window functions (RANK)** to identify top-performing months  
- Applied **CASE statements** to segment sales by time of day  
- Performed **aggregation (SUM, AVG, COUNT)** for business metrics  

---

## 📌 Conclusion
This project demonstrates how SQL can be used to analyze transactional data, uncover trends, and support data-driven business decisions.
