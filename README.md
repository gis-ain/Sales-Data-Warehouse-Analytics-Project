# Sales Data Warehouse & Analytics Project

This repository contains my **second data analytics portfolio project**, focused on building a **star-schema sales data warehouse** and performing exploratory analysis using SQL, Excel, and Power BI.

## Project Overview

The goal of this project is to demonstrate **end-to-end data modeling and analytics skills**, including:

1. **Data Cleaning & Preparation**
   - Raw sales data was cleaned and standardized using Excel.
   - Issues such as missing values, inconsistent text, and duplicate locations were resolved.
   - Dimensions such as `customer`, `product`, `location`, `shipping`, and `date` were created to support a star-schema model using SQL.

2. **Data Modeling**
   - Built a **fact table (`fact_sales`)** and multiple dimension tables (`customer`, `product`, `location`, `shipping`, `date`).
   - Applied **surrogate keys** for dimensions and ensured **referential integrity**.
   - Addressed **duplicate dimension rows** to prevent fact table inflation.
   - Designed **role-playing date dimensions** for order and ship dates.

3. **SQL Implementation**
   - Loaded clean data into MySQL.
   - Implemented joins between fact and dimension tables.
   - Validated data quality using count checks and duplicate detection queries.

4. **Analysis & Visualization**
   - Performed exploratory data analysis (EDA) in **Power BI**.
   - Created insights such as:
     - Profit and sales by region, market, and category
     - Monthly and yearly trends
     - Shipping mode performance
   - Interactive dashboards to communicate business insights.

## Key Learnings

- Understanding **star-schema design** for real-world sales data.
- Handling **data quality issues**, including duplicates and inconsistent records.
- Using **SQL** for ETL, validation, and querying.
- Leveraging **Power BI** for visualization and actionable insights.
- Translating raw operational data into structured, analytics-ready datasets.

## Tools & Technologies

- **Data Cleaning**: Excel
- **Database & ETL**: MySQL
- **Analytics & Visualization**: Power BI
- **Version Control**: GitHub

## Next Steps (To Expand)

- Include more complex **DAX measures** in Power BI.
- Add **time intelligence analysis** (YoY growth, rolling averages).
- Document **lessons learned** and performance optimization techniques.
- Link dashboards to GitHub using images or interactive reports.

---

> This project is intended as a **portfolio demonstration** of my ability to build a **data warehouse from raw sales data**, clean it, model it properly, and extract meaningful insights using SQL and BI tools.
