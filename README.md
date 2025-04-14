# 📊 Layoffs Data EDA Using SQL

This project performs Exploratory Data Analysis (EDA) on a global layoffs dataset using **SQL Server**. The analysis helps uncover trends, patterns, and insights about layoffs across companies, countries, and industries over recent years.

---

## 🚀 Project Overview

The goal of this project is to:
- Explore and analyze the layoffs data using SQL
- Identify which companies, industries, and countries were affected the most
- Understand the timeline and scale of layoffs
- Practice writing efficient SQL queries including CTEs and window functions

---

## 🧰 Tools Used

- **SQL Server** (MS SQL)
- **SQL Server Management Studio** (SSMS)
- Dataset: `world_layoffs.layoffs_staging2`

---

## 🔍 Key Questions Answered

1. **Which companies had the highest number of layoffs?**
2. **What countries and locations were impacted the most?**
3. **Which industries and funding stages saw the most layoffs?**
4. **What year had the highest layoffs?**
5. **How did layoffs trend over months using rolling totals?**
6. **Which companies had 100% of their staff laid off?**
7. **Which companies had the most layoffs year-wise?**
8. **How much funding did companies have before shutting down?**

---

## 🧠 SQL Techniques Used

- `SELECT`, `GROUP BY`, `ORDER BY`, `WHERE`, `LIMIT`
- Aggregation Functions: `SUM()`, `MAX()`, `MIN()`
- Date functions: `YEAR()`, `SUBSTRING()`
- Common Table Expressions (CTEs)
- Window Functions: `DENSE_RANK()`, `SUM() OVER()`

---

## 📈 Sample Insights

- Some startups like **BritishVolt** and **Quibi** raised over $1B and still failed.
- Layoffs peaked in **2022**, hitting companies across industries.
- **Consumer**, **Retail**, and **Transportation** industries were hit hardest.
- Companies like **Better.com** and **Amazon** laid off large numbers in multiple years.
- **Rolling totals** showed steady rises in mid-2022, indicating economic downturn trends.




