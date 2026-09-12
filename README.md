# Sales Performance Dashboard – Power BI

An interactive Power BI dashboard that analyzes sales, profit, and customer data across regions, product categories, and sales representatives to surface actionable business insights.

## 📊 Overview

This project transforms raw sales transaction data into a 3-page interactive report, combining KPI summaries, trend analysis, and geographic/categorical breakdowns to help stakeholders quickly understand business performance.

## 🗂️ Dashboard Pages

### Page 1 — Executive Overview
- KPI Cards: **Total Sales, Total Quantity Sold, Total Cost, Total Profit, Profit Margin %**
- Clustered Column Chart: Sales by Region, broken down by Product Category
- Pie Chart: Profit distribution by Product Category

### Page 2 — Trends & Geography
- Treemap: Sales and Profit by Product Category across Month/Day
- Map Visual: Regional distribution by Customer Type
- Waterfall Chart: Sales Amount progression over time by Category
- Gauge: Total Profit against target

### Page 3 — Sales Rep & Time Analysis
- Line Chart: Monthly Sales Trend
- Clustered Bar Chart: Sales by Region
- Slicer: Filter all visuals by Sales Representative
- Column Chart: Monthly Sales Amount

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** – report building and data modeling
- **DAX (Data Analysis Expressions)** – custom measures: Total Sales, Total Quantity Sold, Total Cost, Total Profit, Profit Margin %
- **Data Modeling** – relationships between Sales and Customer tables
- **Date Hierarchies** – Month/Day drill-down for time-based analysis
- **Data Visualization** – cards, column/bar/pie charts, treemap, waterfall chart, map, gauge, and slicers for interactivity

## 📁 Data Fields Used

| Table | Key Fields |
|---|---|
| Sales | Region, Product_Category, Sale_Date, Sales_Amount, Profit, Customer_Type, Sales_Rep |
| Customer | Total Sales, Total Quantity Sold, Total Cost, Total Profit, Profit Margin % (DAX measures) |

## 🎯 Key Insights Enabled

- Identify top-performing regions and product categories by sales and profit
- Track monthly sales trends to spot seasonality
- Compare performance across sales representatives
- Monitor profit margin health at a glance via KPI cards and gauge

## 🚀 How to View

1. Download `Project.pbix`
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
3. Use the Sales Rep slicer on Page 3 to filter the report interactively

## 📌 Future Enhancements

- Add drill-through pages for individual sales rep performance
- Publish to Power BI Service for web-based sharing
- Add year-over-year comparison visuals
