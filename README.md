# Financial Sales, Product & Expense Analysis

## Project Overview
This project focuses on analyzing business financial performance by examining sales, product profitability, regional expenses, and overall profit.

The objective is to identify profitable products, understand regional performance, track revenue trends, and generate meaningful business insights using data analysis tools.

## Project Objectives
- Analyze total sales and revenue.
- Calculate product costs and profitability.
- Compare revenue and expenses across regions.
- Identify top-performing and low-performing products.
- Analyze monthly sales and revenue trends.
- Evaluate discounts and their impact on profitability.
- Generate actionable business insights.

## Technology Stack
- **Excel:** Data cleaning, formulas, Pivot Tables, charts and financial calculations.
- **SQL (MySQL):** Data extraction, joins, aggregations, CTEs, subqueries and window functions.
- **Python:** Pandas and NumPy for data cleaning, preprocessing and analysis.
- **Power BI:** Interactive dashboards, KPI cards, DAX measures and data visualization.

## Dataset Description

The project uses three datasets:

### 1. Sales Dataset (`sales.csv`)
- Sale ID
- Order Date
- Product ID
- Customer ID
- Region
- Quantity
- Unit Price
- Discount
- Sales Channel

### 2. Products Dataset (`products.csv`)
- Product ID
- Product Name
- Category
- Cost Price

### 3. Expenses Dataset (`expenses.csv`)
- Expense ID
- Expense Date
- Region
- Expense Type
- Expense Amount

## Project Workflow

### 1. Data Cleaning
- Checked and handled missing values.
- Removed duplicate records.
- Corrected data types.
- Standardized column names and formats.
- Prepared datasets for analysis.

### 2. Excel Analysis
- Calculated total revenue, product cost and profit.
- Used IF, SUMIFS, COUNTIFS and lookup formulas.
- Created Pivot Tables for regional and product analysis.
- Analyzed monthly revenue and expenses.
- Identified top-performing products and regions.

### 3. SQL Analysis
- Used INNER JOIN and LEFT JOIN to combine datasets.
- Applied GROUP BY, HAVING and ORDER BY.
- Used aggregate functions such as SUM, AVG and COUNT.
- Implemented CTEs and subqueries.
- Used CASE statements for business categorization.
- Applied window functions such as RANK and LAG.
- Analyzed revenue, expenses, profit and monthly growth.

### 4. Python Analysis
- Loaded datasets using Pandas.
- Performed data cleaning and preprocessing.
- Handled missing and duplicate values.
- Converted date and numerical columns.
- Calculated revenue, cost and profit.
- Analyzed sales performance by product and region.
- Exported summarized results for visualization.

### 5. Power BI Dashboard
Created interactive dashboards to analyze financial performance.

**Dashboard 1: Financial Overview**
- Total Revenue
- Total Expenses
- Total Profit
- Total Quantity Sold
- Monthly Revenue Trend
- Revenue vs Expenses
- Regional Financial Performance

**Dashboard 2: Product & Regional Analysis**
- Top 5 Products by Revenue
- Product-wise Profitability
- Revenue by Category
- Regional Profit Analysis
- Expenses by Type
- Profit Margin Analysis

Interactive slicers were used to filter the reports by region, product category and date.

## Key Business Metrics

| Metric | Calculation |
|---|---|
| Revenue | Quantity × Unit Price × (1 − Discount / 100) |
| Product Cost | Quantity × Cost Price |
| Product Profit | Revenue − Product Cost |
| Net Profit | Total Revenue − Total Expenses |
| Profit Margin | (Net Profit / Revenue) × 100 |
| Discount Amount | Quantity × Unit Price × Discount / 100 |

## Key Business Insights
- Identified top-performing products based on revenue.
- Compared profitability across different product categories.
- Evaluated regional revenue and expense performance.
- Analyzed monthly revenue trends.
- Identified products with low or no sales.
- Examined the relationship between discounts and profitability.
- Highlighted opportunities to improve business performance.

## Project Structure

```text
Financial-Sales-Analysis/
│
├── Dataset/
│   ├── sales.csv
│   ├── products.csv
│   └── expenses.csv
│
├── Excel/
│   └── Financial_Analysis.xlsx
│
├── SQL/
│   └── Financial_Analysis.sql
│
├── Python/
│   └── Financial_Analysis.ipynb
│
├── PowerBI/
│   └── Financial_Dashboard.pbix
│
└── README.md
```

## Conclusion
This project demonstrates practical data analytics skills by combining Excel, SQL, Python and Power BI to transform raw financial data into meaningful business insights.

It provides an understanding of sales performance, product profitability, regional expenses and financial trends to support data-driven business decisions.
