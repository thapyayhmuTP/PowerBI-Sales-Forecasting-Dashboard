# PowerBI-Sales-Forecasting-Dashboard
A comprehensive Power BI dashboard with forecasting, customer insights, product trends, and discount impact simulations for data-driven sales strategy.

This project delivers a strategic sales dashboard using Power BI. It combines forecasting, product analysis, customer segmentation, and a what-if discount simulator to help businesses optimize decisions and drive performance. The dashboard integrates five analytical views and emphasizes interactive exploration, profitability insights, and regional demand.

---

## Project Overview

The model uses a star schema with one fact table (`Sales`), three dimension tables (`Products`, `Customers`, `Date`), and helper tables for slicers, ranking, and discount simulation. The project applies DAX measures, calculated columns, and Power BI's built-in forecasting engine for actionable sales and customer insights.

---

## Key Dashboards & Insights

### 1. Sales Trend Forecast
- Identifies seasonal patterns and future sales using a 12-month forecast
- November shows peak average revenue
- Includes quantity forecast and peak month tracker

### 2. Customer Insights
- Repeat buyers dominate (73.6%) but loyal customers are few
- Most customers fall into low-value groups, suggesting a gap in retention
- Gender, age group, and location filters for segmentation

### 3. Product Analysis
- Product 30 is the top-selling item
- Category distribution is relatively balanced (Clothing leads at 27%)
- Dynamic ranking by product or category using RANKX and slicers
- Treemap, KPI cards, and heatmaps for performance comparison

### 4. Shipping & Regional Analysis
- North region leads in both quantity and order count
- Category demand varies by region (Home is strongest in North/South)
- Lacks shipping mode data; analysis focuses on demand only

### 5. What-If Discount Simulation
- Users can apply discount % via a slider and observe revenue/profit changes
- Forecasting predicts discounted revenue for the next 12 months
- North region shows the highest revenue and profit under discounting

---

## Key Features

- Forecasting with confidence interval (95%) and seasonality (12 months)
- Dynamic slicers: Year, Month, Region, Category, Customer Attributes
- Customer classification by frequency and value
- Discount slider simulation using `GENERATESERIES()` and `SUMX`
- Product ranking with interactive limit control

---

## Team Collaboration

This project was completed as a team assignment for CPSC 510: Data Warehousing & Visualization at the University of Niagara Falls.  
All team members contributed to **visual development**, **insight generation**, and **dashboard improvement suggestions** collaboratively.

---

## Files Included

- `SalesStrategyDashboard.pbix` – Main Power BI file
- `Images` – Dashboard preview images 

---

## Author

Tha Pyay Hmu  
