# Car Sales Performance Dashboard

!\[Screenshot\](img.png)

## Project Overview

This Power BI dashboard offers an in-depth visual analysis of **car sales data** to support strategic decision-making. It highlights essential metrics, sales trends, and profitability drivers across multiple dimensions such as car brands, vehicle conditions, geographic locations, and time periods.

## Project Structure / Methodology

- **Data Cleaning:** Conducted in Python (Google Colab) using pandas for data manipulation and matplotlib/seaborn for exploratory analysis.
- **Preprocessing:** Addressed missing values, filtered out noise, and transformed columns to ensure data quality and consistency.
- **Data Import:** Exported the cleaned dataset as CSV and imported it into Power BI.
- **Data Modelling:** Built relationships between tables representing sales transactions, car attributes, and geographic data.
- **Visualizations:** Created interactive charts (bar, line, pie), KPI cards, and slicers to facilitate user-driven exploration.
- **DAX:** Developed calculated measures and custom metrics for advanced analytics.

## Dependencies

- Python 3.x (pandas, matplotlib, seaborn)
- Power BI Desktop
- Cleaned CSV data from Colab notebook

## Analysis

The dashboard features the following analyses:

- **Average Selling Price by Car Brand and Condition:** Comparing prices across brands and vehicle states (new, used, certified).
- **Ranking of Car Brands by Average Selling Price:** Highlighting brands with premium pricing.
- **Count of Cars Sold by Body Type:** Distribution of sales by vehicle style (SUV, sedan, hatchback, etc.).
- **Drivers of Operating Profit:** Investigating how sales volume, pricing, and costs influence profitability.
- **Cars Sold by State:** Geographic sales breakdown.
- **Selling Price Trends Over Time:** Monitoring price fluctuations monthly or quarterly.
