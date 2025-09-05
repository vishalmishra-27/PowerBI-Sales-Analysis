# Power BI Sales Dashboard Project

## Overview
This project demonstrates an interactive and insightful sales dashboard developed using Microsoft Power BI. It provides detailed analysis of sales data across categories, regions, products, and time periods.

## Features
- Visualizations of revenue by category, region, segment, and top products.
- Time-based analysis with year, quarter, and month breakdowns.
- Interactive filtering by year, country, category, and manufacturer.
- Detailed data model connecting sales, products, manufacturers, calendar, geographical, and population data.
- Key insights into market share, city-wise revenue distribution, and segment performance.

## Screenshots
### Dashboard![Dashboard](Screenshots/Screenshot%202025-09-05%20163205.png)
### DataModel![Data Model](Screenshots/Screenshot%202025-09-05%20164332.png)

## Data Model
The data model uses a star schema connecting:
- Manufacturer
- Product
- Final Sales Fact
- Calendar
- Country Population
- Geographical data

This schema enables multi-dimensional analysis and efficient performance.

## Usage
1. Download the Power BI Desktop file (`SalesDashboard.pbix`).
2. Open the file in Power BI Desktop to explore the interactive reports.
3. Use slicers and filters to analyze sales trends and insights.

## Technical Details
- Source data prepared and cleaned for analysis.
- DAX measures created for key metrics like revenue, units sold, and market share.
- Time intelligence functions used for year-over-year and quarterly trend visualizations.

## Future Enhancements
- Integration with real-time data sources for up-to-date reporting.
- Additional drilldowns and automated notifications.
- Mobile-optimized layouts for on-the-go access.
