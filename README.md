# 📊 Layoffs Data EDA Using SQL

This project performs Exploratory Data Analysis (EDA) on a global layoffs dataset using SQL Server. The analysis helps uncover trends, patterns, and insights about layoffs across companies, countries, and industries over recent years.

## 🚀 Project Overview

The goal of this project is to:
- Explore and analyze the layoffs data using SQL
- Identify which companies, industries, and countries were affected the most
- Understand the timeline and scale of layoffs
- Practice writing efficient SQL queries, including CTEs and window functions

## 🧰 Tools Used
- SQL Server (MS SQL)
- SQL Server Management Studio (SSMS)
- Dataset: `layoffs.csv`

## 🔍 Key Questions Answered
- Which companies had the highest number of layoffs?
- What countries and locations were impacted the most?
- Which industries and funding stages saw the most layoffs?
- What year had the highest layoffs?
- How did layoffs trend over months using rolling totals?
- Which companies had 100% of their staff laid off?
- Which companies had the most layoffs year-wise?
- How much funding did companies have before shutting down?

## 🧠 SQL Techniques Used
- **SELECT, GROUP BY, ORDER BY, WHERE, LIMIT**
- **Aggregation Functions**: `SUM()`, `MAX()`, `MIN()`
- **Date Functions**: `YEAR()`, `SUBSTRING()`
- **Common Table Expressions (CTEs)**
- **Window Functions**: `DENSE_RANK()`, `SUM() OVER()`

## 🧹 Data Cleaning

Before diving into the analysis, the following data cleaning steps were performed:

1. **Handling Missing Values**: 
   - Checked for and handled missing or null values in columns like company names, layoff numbers, and dates. 
   - Missing values were either replaced with default values or removed based on the analysis requirements.
  
2. **Standardizing Date Formats**:
   - The dataset had inconsistent date formats across multiple columns, which were standardized to ensure proper date handling in queries.
  
3. **Removing Duplicates**:
   - Duplicate rows were identified and removed to ensure accurate results from the analysis.
  
4. **Outlier Detection**:
   - Outliers in numerical columns (e.g., unusually high or low layoffs) were examined. In some cases, extreme outliers were removed or adjusted based on domain knowledge.

5. **Data Type Conversions**:
   - Ensured all columns were in the correct data types for analysis (e.g., dates as `DATE` type, numbers as `INT` or `DECIMAL`).

## 📈 Insights & Conclusion

By running the analysis, the following insights were uncovered:
- **Companies with the highest layoffs**: The dataset revealed the companies that laid off the largest number of employees.
- **Impact by location**: Certain countries and locations experienced a higher frequency and scale of layoffs.
- **Industries and funding stages**: Identifying which industries and funding stages were most affected by layoffs.
- **Yearly trends**: Understanding which years had the most layoffs and how the numbers changed over time.
- **Monthly layoffs trends**: Tracking layoffs on a monthly basis, including rolling totals to spot patterns.
- **100% Layoffs**: Identifying companies that had to lay off their entire workforce.
- **Funding insights**: Analyzing the correlation between company funding and layoffs, including companies shutting down after layoffs.

This project provides valuable insights into the global layoffs trend, helping organizations, researchers, and decision-makers better understand workforce changes across industries and locations.
