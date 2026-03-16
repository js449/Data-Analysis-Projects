# Seasonal Data Analysis: Rainfall, Temperature, & Crop Yield

🌦️ Project Overview

This project provides a comprehensive analysis of seasonal weather patterns (Rainfall, Temperature, Humidity) and their direct impact on agricultural yields. The goal was to build a scalable data pipeline that moves raw environmental data from cloud storage into a data warehouse for advanced analytical reporting.

🏗️ Tech Stack
Storage: Amazon S3 (Raw Data Landing)

Data Warehouse: Snowflake (ETL & Analytical Layer)

BI Tool: Power BI (Data Visualization)

Language: SQL (Snowflake Scripting & Integration)

🛰️ System Architecture
Data Ingestion: Raw CSV/JSON datasets are uploaded to an Amazon S3 bucket.

Storage Integration: A secure Snowflake Storage Integration object was created to allow Snowflake to access S3 via IAM Role-based authentication.

Data Transformation: \* Created External Stages and File Formats.

Structured raw data into Snowflake tables using COPY INTO commands.

Applied data cleaning (handling nulls, unit conversions) within Snowflake.

Reporting: Connected Power BI to Snowflake to create a dynamic dashboard.

📊 Key Insights & Features
Correlation Analysis: Investigated the relationship between humidity levels and crop yield volatility.

Seasonal Trends: Identified averages (rainfall, temperature, yield) and their historical impact on seasonal harvesting.

📂 Repository Structure

├── data/

├── snowflake_scripts/Seasondata

├── powerbi/Report

└── README.md

🚀 How to Replicate
AWS Setup: Create an S3 bucket and an IAM role with the necessary S3 permissions.

Snowflake Setup: \* Run the scripts in snowflake_scripts/ to create the storage integration.

Set up the external stage pointing to your S3 bucket.

Power BI:

Open the .pbix file.

Update the Data Source settings to point to your Snowflake Account and Warehouse.

📸 Dashboard Preview
(Rainfall_Analysis.png)
![Executive Dashboard](Humidity_Analysis.png)
![Executive Dashboard](Temp_Analysis.png)
![Executive Dashboard](Yield_Analysis.png)
