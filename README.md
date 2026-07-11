# 👟 Adidas Sales Analysis Dashboard | Power BI

## Dashboard Preview

![Dashboard](DASHBOARD.png)

---

## Project Overview

This project presents an interactive Adidas Sales Analysis Dashboard developed using Power BI, Power Query, DAX, and Data Modeling techniques.

The dashboard provides a comprehensive analysis of Adidas sales performance across different states, regions, retailers, and product categories. It enables stakeholders to monitor revenue, profitability, sales trends, and key business metrics through dynamic filters and visualizations.

---

## Business Objective

The primary objective of this dashboard is to:

- Analyze overall sales performance.
- Monitor profitability and business growth.
- Identify top-performing products and retailers.
- Compare regional and state-wise sales.
- Discover sales trends over time.
- Support data-driven decision-making.

---

## Tools & Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Interactive Slicers
- KPI Cards
- Excel Dataset

---

## Dataset Information

The dataset contains Adidas sales transaction data including:

- Invoice Date
- Region
- State
- Retailer
- Product Category
- Units Sold
- Price Per Unit
- Total Sales
- Operating Profit
- Operating Margin
- Sales Method

---

## Data Preparation

Data transformation and cleaning were performed using Power Query.

### Steps Performed

1. Imported raw sales dataset.
2. Removed duplicate records.
3. Handled missing values.
4. Corrected data types.
5. Standardized column names.
6. Created calculated columns and measures.
7. Built relationships between tables.
8. Developed DAX measures for KPIs.
9. Created an interactive Power BI dashboard.

---

## DAX Measures Used

### Total Sales

```DAX
Total Sales =
SUMX(
    'Dataset',
    'Dataset'[Price per Unit] * 'Dataset'[Units Sold]
)
```

### Total Profit

```DAX
Total Profit =
SUM('Dataset'[Operating Profit])
```

### Total Units Sold

```DAX
Total Unit Sold =
SUM('Dataset'[Units Sold])
```

### Average Price Per Unit

```DAX
Average Price Per Unit =
AVERAGE('Dataset'[Price per Unit])
```

### Profit Margin

```DAX
Profit Margin =
AVERAGE('Dataset'[Operating Margin])
```

---

## Dashboard Features

### KPI Cards

- Total Sales: $295.59M
- Total Profit: $107.99M
- Total Units Sold: 6M
- Average Price Per Unit: 42.03
- Profit Margin: 39.49%

### Monthly Sales Trend

- Analyzes monthly sales performance.
- Identifies peak and low-performing months.
- Supports trend analysis and forecasting.

### State Wise Sales Analysis

- Interactive map visualization.
- Highlights sales distribution across states.
- Helps identify high-performing markets.

### Region Wise Sales Analysis

- Compares regional sales contribution.
- Provides insights into geographic performance.

### Product Wise Sales Analysis

- Identifies top-performing product categories.
- Compares sales across product segments.

### Retailer Wise Sales Analysis

- Analyzes retailer contribution to total sales.
- Highlights top-performing retail partners.

---

## Key Business Insights

- Total Sales exceeded $295 Million.
- Total Profit reached approximately $108 Million.
- Profit Margin remained strong at 39.49%.
- West Region contributed the highest sales.
- Men's Street Footwear generated the highest revenue.
- Foot Locker emerged as the top-performing retailer.
- January recorded the highest monthly sales.
- June recorded the lowest monthly sales.

---

## Project Outcome

This dashboard helps business stakeholders monitor sales performance, evaluate profitability, identify top-performing products and retailers, and make informed business decisions using interactive visual analytics.

---

## Repository Structure

ADIDAS-SALES-ANALYSIS-DASHBOARD/

├── ADIDAS SALES ANALYSIS DASHBOARD.pbix

├── DASHBOARD.png

├── README.md

---

## Author

### Priti Borde

MBA (Agri Business & International Business)

Data Analytics Learner

### Technical Skills

- Power BI
- Power Query
- DAX
- Excel
- SQL
- Python
- Statistics
- Data Visualization

---

## Repository Description

Interactive Adidas Sales Analysis Dashboard built using Power BI, Power Query, and DAX to analyze sales performance, profitability, regional trends, retailer contribution, and product-wise insights through dynamic visualizations and business intelligence reporting.
