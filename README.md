# Mini Data Warehouse Learning Project

## Overview
This project was created as a small learning initiative to understand the fundamentals of Data Warehousing. The goal was to build a simple end-to-end solution that collects transactional data, transforms it, and stores it in a structured analytical model for reporting and analysis.

## Objectives
- Learn Data Warehouse concepts and architecture.
- Practice ETL (Extract, Transform, Load) processes.
- Design a Star Schema with fact and dimension tables.
- Create basic analytical reports and KPIs.

## Architecture
Source Data → ETL Process → Data Warehouse → Reporting Layer

### Main Components
- **Source System:** Sales transaction data.
- **ETL Process:** Data cleansing, transformation, and loading.
- **Data Warehouse:** Star Schema model.
- **Reporting:** Simple dashboards and SQL queries.

## Data Model

### Fact Table
- FactSales
  - OrderID
  - ProductID
  - CustomerID
  - DateID
  - SalesAmount
  - Quantity

### Dimension Tables
- DimCustomer
- DimProduct
- DimDate

## Key Learnings
- Difference between OLTP and OLAP systems.
- Importance of data quality and consistency.
- Fact vs Dimension tables.
- Star Schema design principles.
- Basic performance optimization techniques.

## Technologies Used
- SQL Server
- SQL (T-SQL)
- ETL Scripts
- Power BI (optional)

## Outcome
Successfully built a small Data Warehouse that supports sales analysis, customer insights, and product performance reporting while gaining hands-on experience with core Data Engineering and Business Intelligence concepts.
