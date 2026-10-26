# Adventure-Works-Power-BI-Dashboard
# Adventure Works Case Study | Power BI Dashboard

## 📌 Project Overview

Adventure Works is an end-to-end Power BI data analytics case study focused on transforming raw business data into meaningful insights through interactive dashboards.

The project analyzes sales performance, product trends, customer behavior, profitability, returns, and geographical distribution through three analytical dashboards:

- **Category-Level Analysis**
- **Product-Level Analysis**
- **Customer-Level Analysis**

The report incorporates data transformation, data modeling, relationship management, DAX measures, KPI tracking, and interactive visualizations to evaluate business performance and support data-driven decision-making.

## 🎯 Project Objectives

- Analyze total revenue, quantity sold, and order performance.
- Evaluate sales and return trends across product categories.
- Identify top-performing and low-performing products.
- Analyze product profitability, costs, and return rates.
- Compare weekday and weekend order patterns.
- Track return trends and revenue changes over time.
- Analyze geographical distribution of orders.
- Compare actual orders against business targets.
- Identify high-value customers and their revenue contribution.
- Explore customer demographics by age, gender, occupation, education, and income.

## 📊 Dashboard Pages

### 1. Category-Level Analysis

Provides an overview of sales and return performance across product categories and subcategories.

**Key Performance Indicators (KPIs)**
- Total Revenue
- Quantity Sold
- Total Orders
- Total Return Quantity
- Total Return Amount

**Key Analysis**
- Revenue and quantity sold by category
- Return quantity and return rate by category
- Bulk orders and high-ticket orders
- Weekday vs. weekend order patterns
- Order percentage contribution by category
- Return rates by subcategory and product

**Business Value:** Identifies revenue-driving categories, order contribution, and product segments with higher return rates.

### 2. Product-Level Analysis

Focuses on individual product performance, profitability, return activity, and sales trends.

**Key Performance Indicators (KPIs)**
- Most Ordered Product
- Total Profit
- Total Cost
- Most Profitable Product

**Key Analysis**
- Product returns per week
- Category-based product filtering
- Order trends by year
- Total orders by country
- Weekly profit trends
- Actual orders vs. order targets

**Business Value:** Helps identify best-selling and most profitable products, monitor return activity, evaluate geographical performance, and track progress against business targets.

### 3. Customer-Level Analysis

Explores customer purchasing behavior, demographics, and revenue contribution.

**Key Performance Indicators (KPIs)**
- Top Customer Revenue
- Highest-Revenue Occupation
- Highest-Revenue Customer

**Key Analysis**
- Customer-wise revenue and total orders
- Current month vs. previous month revenue
- Revenue by age group
- Orders by gender
- Customer distribution by income category
- Customer analysis by education level

**Business Value:** Highlights high-value customers and reveals purchasing patterns across different demographic and socioeconomic segments.

## 🗂️ Data Model

The Power BI data model consists of fact tables and dimension tables connected through relationships to enable consistent filtering and analysis across dashboards.

**Fact Tables**

| Table | Description |
|---|---|
| Sales | Transaction-level sales data, including customer key, product key, order date, order number, quantity, and line item |
| Returns | Product return data, including product key, return date, return quantity, and territory key |

**Dimension Tables**

- Customers
- Products
- Subcategories
- Categories
- Territories
- Calendar

The relationships between fact and dimension tables support multi-level analysis of sales, products, returns, customers, and geographical performance.

**Data Model / ER Diagram**

![Adventure Works ER Diagram](Data-Model/ER_Diagram.png)

## 🧮 DAX Measures & Calculations

DAX was used to develop business measures, dynamic KPIs, and analytical calculations.

**Key Measures**
- Total Revenue
- Total Orders
- Total Quantity Sold
- Total Cost and Total Profit
- Total Return Quantity and Return Amount
- Return Rate
- Previous Month Revenue
- Current vs. Previous Month Comparison
- Revenue Growth
- Order Percentage by Category
- Most Ordered Product
- Most Profitable Product
- Top Customer Revenue
- Weekly Profit
- Order Target Comparison
- Weekday vs. Weekend Orders

**DAX Functions & Concepts**
`CALCULATE()` · `SUM()` · `SUMX()` · `COUNT()` · `RELATED()` · `IF()`

Additional concepts include filter context, context modification, and date-based calculations.

## 💡 Key Business Questions

The dashboards help answer questions such as:

- Which product category generates the highest revenue?
- Which categories and products have the highest return rates?
- Which products are the most ordered and most profitable?
- How does revenue and profitability change over time?
- Are more orders placed on weekdays or weekends?
- Which countries generate the highest number of orders?
- How are actual orders performing against targets?
- Which customers and occupations contribute the most revenue?
- Which age groups generate the highest revenue?
- How do purchasing patterns vary by gender, income, and education?

## ✨ Dashboard Features

- Interactive KPI cards
- Bar, line, and area charts
- Treemap, pie, and donut charts
- Geographical map visualizations
- Tables and conditional formatting
- Category and education-level slicers
- Year-range filters
- Cross-filtering between visuals
- Multi-level business performance analysis

## 🖼️ Dashboard Previews

### Category-Level Dashboard

![Category-Level Dashboard](Dashboard-Screenshots/Category_Dashboard.png)

Analyzes category-wise revenue, quantity sold, orders, returns, return rates, and overall sales contribution.

### Product-Level Dashboard

![Product-Level Dashboard](Dashboard-Screenshots/Product_Dashboard.png)

Highlights product performance, profitability, return trends, geographical distribution, and order targets.

### Customer-Level Dashboard

![Customer-Level Dashboard](Dashboard-Screenshots/Customer_Dashboard.png)

Explores customer revenue, purchasing behavior, occupation, age groups, gender, income, and education.

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Power BI | Dashboard development and business analytics |
| Power Query | Data cleaning, transformation, and preparation |
| DAX | Measures, KPIs, and business calculations |
| Data Modeling | Fact and dimension table relationships |
| Data Visualization | Presenting trends and business insights |

## 📚 Skills Demonstrated

- Power BI Dashboard Development
- Data Cleaning and Transformation
- Data Modeling and Relationship Management
- DAX Measures and KPI Development
- Sales, Revenue, and Profitability Analysis
- Product Performance and Return Analysis
- Customer Segmentation and Demographic Analysis
- Geographical and Time-Based Analysis
- Interactive Report Design
- Business Intelligence and Data-Driven Decision-Making

## ✅ Conclusion

This project demonstrates the use of Power BI to transform business data into actionable insights through data modeling, DAX calculations, KPI development, and interactive visualizations.

The three dashboards provide a consolidated view of category performance, product profitability, customer behavior, sales trends, returns, and geographical distribution, enabling a deeper understanding of business performance.

## 👤 Author

**Sarthak Bansla**  
Aspiring Data Analyst

**Skills:** Excel | SQL | Power BI | Python | Statistics
