# RetailPulse – Retail Analytics & Intelligence Dashboard

### Zidio Internship Project | Microsoft Power BI

## Project Overview

RetailPulse is a retail analytics and intelligence dashboard designed to explore sales performance, geographical revenue distribution, customer segmentation, and inventory-related analytics.

The project uses the Online Retail II dataset and a mentor-provided Power BI report as its starting point.

**Implementation:** Microsoft Power BI Desktop  
**Dataset:** Online Retail II  
**Dashboard Pages:** 4  
**Internship:** Zidio

## Dashboard Modules

### 1. Sales Overview
- Total Revenue, Orders, Quantity, and Customers
- Average Order Value (AOV)
- Revenue trends
- Monthly and hourly sales analysis

### 2. Geography & Categories
- Country-wise revenue comparison
- Product category revenue visualization
- Country and category sales matrix

### 3. Customer Intelligence
- Customer segmentation distribution
- Segment-based revenue analysis
- Customer Lifetime Value visualization
- Customer-level metrics and churn indicators

### 4. Operations & Model Health
- Revenue and order KPIs
- Product distribution by category
- Inventory-related analysis
- Forecasting model metrics

## My Power BI Contributions

Starting from the mentor-provided report, I worked on:

- Creating a separate working copy of the Power BI dashboard.
- Inspecting the data model and relationships.
- Creating a DAX measure for Average Order Value.
- Improving the sales trend visualization.
- Correcting the country/category matrix using transaction-level fields.
- Improving customer table presentation.
- Replacing an overcrowded inventory visualization with a readable category distribution.
- Reviewing misleading aggregations and improving report presentation.

## Technology Used

- Microsoft Power BI Desktop
- DAX
- Power Query (inspection)
- Retail transaction and summary datasets

## Important Limitations

- Some original data sources reference file paths that are not available on other computers. Refreshing the report may require reconnecting the source files.
- The supplied churn-model evaluation contains a potential data-leakage issue and should not be interpreted as independently validated prediction accuracy.
- Some forecasting metrics were calculated using non-independent evaluation data.
- Inventory simulation outputs are not verified improvements in real retail operations.
- Figures and calculations should be validated before production use.

## Project Files

- `retailPulse_final.pbix` – Updated Power BI report
- `RetailPulse_Dashboard.pdf` – Four-page dashboard preview
- `RetailPulse_Project_Report.pdf` – Project documentation (to be added)

## Attribution

This project was completed as part of a Zidio internship assignment. The starter Power BI dashboard and associated project materials were supplied by the internship mentor.

The contributions described above represent my own dashboard inspection, configuration, measure creation, visual modifications, and documentation work.

## Project Status

Power BI dashboard updated. Documentation and demonstration materials are being prepared.
