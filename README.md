# Real Estate & Housing Market Analysis Dashboard (BigQuery + Power BI) 🏡📊
**Project Overview**

This project delivers an end-to-end (E2E) solution for analyzing housing market trends and sales performance, leveraging the power of Google BigQuery as a scalable, cloud-based data source and Power BI for dynamic visualization.
The pipeline included setting up the Google Cloud environment, loading raw data into BigQuery, performing initial SQL transformations, and establishing a robust connection to Power BI. The final dashboard provides deep insights into sales growth, pricing volatility, and regional performance to guide strategic business decisions

**Architecture and Key Technologies 🛠️**

1)Cloud Data Warehouse:	Google BigQuery ☁️,	Used as the primary data source; data loaded, profiled, and pre-transformed using SQL queries before ingestion into Power BI.

2)ETL & Cleaning:	Power Query Editor,	Performed data cleaning, including null replacement (e.g., city, annual inflation rate) and data type verification, to ensure data readiness.

3)DAX & Modeling:	DAX (Data Analysis Expressions),	Developed complex time-intelligence and statistical measures, including: Year-on-Year (YOY) Sales Growth, MedianX Sales Price Change, TOTALYTD Sales, Last 12 Months Sales, and Price per Square Meter (SQM).

4)Feature Engineering:	Calculated and derived columns for enhanced analysis, such as Age of the property and Offer Price.
Advanced Visualization	Power BI	Implemented visuals like Key Influencers (analyzing purchase price vs. property age), Scatter Plot (price relationship), Combo Chart, and custom-formatted slicers for dynamic filtering.

5)Deployment:	Power BI Service,	Managed workspaces and published the final multi-page report for sharing and enterprise consumption.

**Dashboard Features & Key Analysis 📈:**
The report is segmented into pages focusing on different aspects of the market:

1)Sales Performance: Tracks YOY sales growth, total sales by region, and YTD sales trends.

2)Pricing Analysis: Visualizes the relationship between purchase price, offer price, and calculates the Median Sales Price Change by region.

3)House Type Analysis: Compares average offer price and purchase price across different house types.

4)Market Influencers: Uses the Key Influencers visual to understand factors driving property purchase price.

**Repository Files 📁**
Housing Data.csv: The original housing/sales dataset.

[Sales Performance].png: Screenshot of the Sales Performance page.

[House Market Analysis].png: Screenshot of the House Type Analysis page.

[Overall].png: Screenshot of the Overall Analysis page.
