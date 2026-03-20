# Microsoft Fabric End-to-End Sales Analytics Project

## Project Overview
Built a complete data pipeline using Microsoft Fabric 
to analyze sales data from ingestion to visualization.

## Architecture
Raw Data → Bronze Lakehouse → Silver Lakehouse → Power BI Dashboard

## Tools & Technologies Used
- Microsoft Fabric (Lakehouse, Dataflow Gen2, Notebooks)
- PySpark (data_cleaning notebook)
- SQL analytics endpoint
- Power BI Desktop (relationships, DAX measures, reports)
- Delta Lake / OneLake storage

## Project Steps
1. Ingested raw data into Bronze Lakehouse
2. Cleaned and transformed data using Dataflow Gen2
3. Built Silver layer with clean tables
4. Connected Power BI Desktop via SQL Server connector
5. Built relationships between tables
6. Created DAX measures for revenue analysis
7. Built interactive sales dashboard

## Screenshots
[Add your screenshots here]

## Key Learnings
- Medallion architecture (Bronze → Silver → Gold)
- Dataflow Gen2 for ETL transformations
- Power BI Direct connectivity with Fabric
- DAX measures for business KPIs
