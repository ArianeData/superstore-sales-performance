# Superstore Sales Performance Dashboard (Excel)

## Project Overview
This project analyzes retail sales performance using the Superstore dataset.  
The goal was to transform raw transactional data into actionable business insights and build an interactive Excel dashboard.

The dashboard allows users to explore revenue, profitability, customer performance, and seasonal trends using interactive filters.

---

## Business Problem
Retail companies generate large volumes of transactional data but often struggle to extract meaningful insights.

This project aims to answer key business questions:

- How is overall sales performance evolving over time?
- Which product categories generate the most revenue and profit?
- Which regions are the most profitable?
- Who are the top customers driving revenue?
- Are there seasonal sales patterns?

---

## Data Preparation
Before analysis, the dataset required several cleaning steps:

- Corrected **data type and locale issues** during import to ensure proper interpretation of dates and decimal values.
- Removed duplicate records based on **Order ID and Product ID**
- Standardized text fields (Customer Name, Country, State, City, Segment)
- Created new time variables (Order Year, Month Name, Month Number)

---

## Key Performance Indicators

- Total Revenue: €2,295,509  
- Total Profit: €286,013  
- Profit Margin: 12.46%  
- Number of Orders: 9,986  
- Average Order Value: €229.87  

---

## Key Business Insights

- Technology generates the highest revenue and profit.
- The West region shows the strongest performance.
- Sales increased significantly in 2017 compared to previous years.
- A small number of customers contribute a large share of total revenue.
- Seasonal patterns exist in monthly sales performance.

---

## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Data Cleaning Functions
- Interactive Slicers

---

## Dashboard Preview

![Dashboard](Superstore_dashboard_preview.PNG)


---

## Files in This Repository

- **Superstore_Raw_Data.csv** -- Original dataset  
- **Superstore_Sales_Dashboard.xlsx** -- Final Excel dashboard and analysis  
- **Superstore_dashboard_preview.png** -- Dashboard screenshot preview

## Future Improvements

- Rebuild the dashboard using **Power BI**
- Perform deeper analysis using **SQL**
- Conduct advanced analysis with **Python**
