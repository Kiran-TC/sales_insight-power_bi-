This project focuses on analyzing sales performance using Power BI. It involves data cleaning and transformation using SQL, ETL modeling within Power BI, structured measure creation, and building a comprehensive dashboard to uncover actionable insights.

⚙️ Tech Stack
SQL – Data Cleaning and Preprocessing

Power BI – Data Modeling, ETL, Visualization

DAX – Measure and KPI calculations

🚀 Project Steps
1. 📥 Data Extraction & Cleaning (SQL)
Loaded raw sales data from SQL dump (db_dump.sql)

Cleaned and normalized tables (e.g., handled nulls, corrected data types, removed duplicates)

Created joins between sales, customers, products, and regional tables using SQL queries

Filtered irrelevant rows and standardized categorical fields

2. 🔄 ETL Process in Power BI
Imported cleaned SQL data into Power BI using the SQL Server connector

Applied Power Query Editor for:

Renaming columns for clarity

Changing data types

Merging and appending queries as required

Creating calculated columns for key metrics (e.g., Sales Value = Quantity × Price)

3. 🧱 Data Modeling
Established star schema model with fact and dimension tables

Defined proper relationships (1: or :1) using foreign keys

Removed unnecessary tables and columns for performance optimization

4. 📐 Measure Creation & KPI Calculation
Created a separate "Base Measures" table to manage all DAX measures in one place

Used DAX formulas to define calculated metrics

5. 📊 Report & Dashboard Design
Built multiple pages of interactive visuals:

Sales by Region, Category, and Sub-Category

Profit Trend Over Time

Discount Impact on Profitability

Top Performing Products and Customers

Enabled drill-through and tooltips for better interactivity

Applied slicers and filters for date, region, and customer segments

📈 Key Outcomes
Reduced reporting time by 75% through automation

Enabled data-driven decisions with a 20% improvement in regional strategy

Centralized KPI tracking using modular measures

