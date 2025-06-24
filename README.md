# Sales Analytics Project

## Overview
This project analyzes sales data from multiple platforms (City Hive, Uber Eats, DoorDash, and Flaviar) to track performance metrics, identify trends, and provide insights for business decision-making. The analysis covers the period from March 2023 to March 2025, with a focus on comparing year-over-year performance.

## Key Metrics Analyzed
- **Overall Sales Performance**: Comparison of total sales across platforms between two periods (Mar 2023-Mar 2024 vs Mar 2024-Mar 2025)
- **Monthly Revenue Trends**: Breakdown of sales by month for each platform
- **Customer Acquisition**: Analysis of new customers gained in each period
- **Customer Retention**: Tracking total unique customers across periods
- **Purchase Frequency**: Total number of purchases in each period
- **Platform Contribution**: Percentage breakdown of sales by platform
- **Average Order Value (AOV)**: Comparison of AOV across different platforms

## Visualizations
The project includes several visualizations to help interpret the data:
- Bar charts comparing period-over-period performance
- Monthly revenue histograms
- Pie charts showing platform contribution to overall sales
- Line charts tracking monthly sales trends
- Bar charts comparing AOV across platforms

## Data Sources
The analysis uses data from four main sources:
- City Hive YTD.xlsx
- Uber YTD.xlsx
- Doordash YTD.xlsx
- Flaviar YTD.xlsx

## Requirements
- Python 3.x
- pandas
- matplotlib
- seaborn
- openpyxl (for Excel file handling)

## Setup and Usage
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Place the data files in the project directory
4. Run the analysis scripts

## File Structure
```
sales-analytics-project/
├── README.md
├── requirements.txt
├── analysis.py
├── data/
│   ├── City Hive YTD.xlsx
│   ├── Uber YTD.xlsx
│   ├── Doordash YTD.xlsx
│   └── Flaviar YTD.xlsx
└── output/
    ├── overall_sales_comparison.png
    ├── monthly_revenue.png
    ├── new_customers_comparison.png
    ├── purchases_comparison.png
    ├── customers_comparison.png
    ├── sales_percentage_piechart.png
    ├── monthly_sales_trends.png
    └── aov_by_platform.png
```

## Key Findings
- Overall sales growth rate between the two periods
- Platform-specific performance trends
- Customer acquisition and retention metrics
- Seasonal patterns in sales data
- Relative performance of different sales channels

## Future Enhancements
- Predictive analytics for future sales forecasting
- Customer segmentation analysis
- Product category performance analysis
- Geographic sales distribution analysis
- Integration with real-time data sources
