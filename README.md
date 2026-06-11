



# Sales Performance Dashboard (Power BI)

## Project Overview
This Power BI project provides an interactive Sales Performance Dashboard designed to help business stakeholders monitor revenue, profitability, product performance, discounts, customer orders, and geographic sales distribution.

The dashboard enables users to analyze sales trends, compare performance across time periods, identify top and bottom performing products, and drill down into order-level details using interactive filters and slicers.

---

## Business Requirements & Solution Design

### 1. Top/Bottom 5 Products by Sales, Profit, and Quantity Sold
**Objective:** Identify best and worst performing products.

**Suggested Visuals**
- Clustered Bar Chart
- Dynamic Top N Filter

**Measures**
- Total Sales
- Total Profit
- Total Quantity Sold

**Insights**
- Best-selling products
- Low-performing products requiring attention

---

### 2. Sales Trend Analysis Over Time
**Objective:** Understand how sales change across different time periods.

**Granularity**
- Daily
- Monthly
- Quarterly
- Yearly

**Suggested Visuals**
- Line Chart
- Area Chart

**Insights**
- Seasonality
- Growth trends
- Peak sales periods

---

### 3. Relationship Between Sales and Profit
**Objective:** Analyze profitability against revenue.

**Suggested Visual**
- Scatter Plot

**Configuration**
- X-Axis: Sales
- Y-Axis: Profit
- Bubble Size: Quantity Sold
- Legend: Product Category

**Insights**
- High sales but low profit products
- Most profitable categories

---

### 4. Compare Sales, Profit & Quantity Between Two User-Selected Periods
**Objective:** Enable period-over-period comparison.

**Suggested Visuals**
- KPI Cards
- Clustered Column Charts
- Variance Cards

**Filters**
- Date Slicers

**Metrics**
- Current Period Sales
- Previous Period Sales
- Growth %
- Profit Variance
- Quantity Variance

---

### 5. Average Discount by Discount Category
**Objective:** Evaluate discounting strategy.

**Suggested Visuals**
- Column Chart
- Matrix

**Measure**
- Average Discount

**Insights**
- Categories receiving the highest discounts
- Impact of discount strategy

---

### 6. Total Number of Orders
**Objective:** Monitor order volume.

**Suggested Visual**
- KPI Card

**Measure**
- Distinct Count of Order ID

---

### 7. Order-Level Detailed Analysis
**Objective:** Allow detailed transaction analysis.

**Suggested Visual**
- Table / Matrix

**Fields**
- Order ID
- Order Date
- Customer ID
- Product
- Sales
- Profit
- Discount
- Net Sales
- Quantity
- Promotion Category

**Interactive Filters**
- Product
- Date
- Customer ID
- Promotion Category

---

### 8. Sales by City
**Objective:** Analyze geographical performance.

**Suggested Visuals**
- Map
- Filled Map
- Bar Chart

**Insights**
- Top-performing cities
- Regional sales distribution

---

## Dashboard Pages

### Executive Summary
- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold
- Sales Trend
- Sales by City

### Product Performance
- Top/Bottom Products by Sales
- Top/Bottom Products by Profit
- Top/Bottom Products by Quantity

### Profitability Analysis
- Sales vs Profit Relationship
- Discount Analysis
- Profit Margin Analysis

### Period Comparison
- Current vs Previous Period Analysis
- Growth Metrics

### Order Details
- Transaction-Level Data
- Interactive Filters

---

## Data Model

### Fact Table
FactSales

### Dimension Tables
- DimDate
- DimProduct
- DimCustomer
- DimPromotion
- DimLocation

### Recommended Schema
Star Schema

---

## Key KPIs

- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold
- Average Discount
- Net Sales
- Profit Margin %
- Sales Growth %

---

## Power BI Features Used

- Data Modeling
- Power Query
- DAX Measures
- Time Intelligence
- Drill Through
- Slicers
- Bookmarks (Optional)
- Dynamic Top N Analysis

---

## Business Value

This dashboard helps stakeholders:

- Track sales performance in real time
- Identify profitable products and cities
- Analyze discount effectiveness
- Compare performance across time periods
- Monitor order activity
- Support strategic business decisions

---

## Tools & Technologies

- Power BI Desktop
- DAX
- Power Query
- Star Schema Data Modeling
- GitHub

---

## Author

Rohan

Power BI Sales Performance Dashboard Project




