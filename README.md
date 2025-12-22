# Customer Mapping & Sales Analysis

## Project Overview
This project analyzes customer behavior, sales performance, and regional trends using a star schema data model.  
The goal was to transform raw transactional data into an analytics-ready structure that supports efficient querying and Power BI reporting.

## Business Questions
1. What are the monthly trends in online vs in-store sales for 2021, and how do they project forward based on assumed growth?
2. Which customer segment generates the highest revenue in each region, and how does this change month-over-month?

## Data Modeling Approach
- Designed a **star schema** with:
  - Dimension tables: Customer, Product, Store, Promotion
  - Fact table: Customer Transactions
- Implemented using SQL to support BI tools and scalable analysis.

## Tools Used
- SQL Server
- Power BI
- Excel
- PowerPoint

## Key Insights
- In-store sales consistently outperformed online sales throughout 2021.
- Consumer customers generated the highest revenue across all regions.
- Sales trends showed strong seasonality, supporting reliable forecasting.

## Deliverables
- SQL scripts for data modeling
- Star schema diagram
- Power BI dashboard
- Business insights and recommendations

## Data Model

The project uses a star schema design to support efficient querying and BI reporting.

**Fact Table**
- FactCustomerTransactions

**Dimension Tables**
- DimCustomer
- DimProduct
- DimStore
- DimPromotion

![Star Schema Diagram](VISUALS/star_schema_diagram.png)

