# Dominicks-Finer-Foods-OLAP-Data-Warehousing

## Overview
This project focused on designing and implementing an OLAP data warehousing solution for Dominick’s Fine Food, a grocery chain in the Chicago area. The goal was to centralize store-level data and create a system to support reporting and visualization for key business decisions.

## Objectives
Design and implement a data warehouse using industry-standard tools.
Build dashboards to address specific business use cases.
Enable multi-dimensional analysis using SSAS cubes for deeper insights.

## Approach
### 1. Data Collection and Understanding:
- Gathered store-level data related to sales, pricing, and inventory.
- Conducted data profiling to identify patterns, missing values, and inconsistencies.
### 2. Database Design:
- Designed the warehouse schema following the Kimball methodology.
- Created star schema models with fact tables for transactions and dimension tables for products, stores, customers, and time.
### 3. ETL Process:
- Built an ETL pipeline using SSIS to extract data from source systems, transform it for consistency, and load it into the data warehouse.
- Applied transformations to calculate metrics like sales trends, stock levels, and product profitability.
### 4. Analysis and Reporting:
- Developed interactive dashboards in Tableau and Power BI to visualize insights.
- Designed reports in SSRS for operational and strategic analysis.
- Enabled multi-dimensional data exploration using SSAS cubes to allow slicing and dicing by time, product, and store dimensions.
### 5. Business Use Cases Delivered:
- Sales Performance Analysis: Dashboards showing sales trends by product category, store, and time period.
- Pricing Optimization: Insights into pricing strategies and their impact on sales volume and revenue.
- Inventory Management: Reports tracking stock levels, identifying overstocked or understocked products.
- Customer Insights: Analysis of customer behavior, including purchase patterns and loyalty metrics.
### 6. Validation and Optimization:
- Verified the accuracy of data and reports by cross-referencing with source systems.
- Optimized query performance to ensure efficient data retrieval for dashboards and reports.

## Tools and Technologies
- SSMS for database management and query development.
- SSIS for building ETL pipelines.
- SSRS for creating paginated reports.
- SSAS for building analytical cubes.
- Tableau and Power BI for creating interactive dashboards.

## Key Deliverables
- A fully functional data warehouse tailored to Dominick’s Fine Food’s business needs.
- Interactive dashboards and reports addressing critical business questions.
- Multi-dimensional analysis capabilities using SSAS cubes.


**Note:** This repository and its contents are the intellectual property of Sai Krishna Koppula. Any unauthorized
reproduction, distribution, or use of this material, in part or whole is strictly prohibited. Violators
may be subject to plagiarism penalties and other legal or academic consequences.