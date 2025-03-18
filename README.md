The project involves creating a DataWareHouse from CSV files from two different sources (ERP & CRM) and then creating a Medallion data architecture that divides the ETL process into Gold,Silver and Bronze layers with well defined seperation of concerns.
Each layer is developed and segregated with the industry adopted best practices to prepare the data ready for consumption.
This project also includes data analysis using MS SQL server queries and communication of business insights.
Its is a complete end to end project to demonstrate the ETL,Storage,Data Prep and Data Analysis process as per indstry adopted practices.

# Data Architecture
![image](https://github.com/user-attachments/assets/83138a89-9700-4a37-a8cb-319b23c630cc)

   * Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
   * Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
   * Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

# Project Overview
This project involves:

    Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
    ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
    Data Modeling: Developing fact and dimension tables optimized for analytical queries.
    Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.
# Project Requirements  
*Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.
Specifications

    Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
    Data Quality: Cleanse and resolve data quality issues prior to analysis.
    Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
    Scope: Focus on the latest dataset only; historization of data is not required.
    Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
# Business Intelligence Analysis & Reporting
Objective

Develop SQL-based analytics to deliver detailed insights into:

    Customer Behavior
    Product Performance
    Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

# About Me:-
Hi there! I'm Siddhartha Kumar Jha. I am passionate about learning technology and working with data to drive decisions.
