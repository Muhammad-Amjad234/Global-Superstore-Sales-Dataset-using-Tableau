# Global Superstore 2016 Orders Dashboard

## Overview

This repository documents a Tableau dashboard for the **Global Superstore 2016 Orders** dataset. It provides key insights into sales, profitability, shipping, and order management using various visualizations.

## Dataset

The dashboard uses `global_superstore_2016.xlsx - Orders.csv`, a dataset containing transactional data from 2016. Key attributes include:

- **Sales Figures**
- **Product Information** (Categories, Sub-categories)
- **Geographical Data** (Regions, Countries, Cities)
- **Shipping Details** (Mode, Cost, Dates)
- **Order Management** (Date, ID, Priority)
- **Customer Information**
- **Profitability Metrics** (Profit, Profit Margin)

The dataset has been prepared for Tableau.

## Dashboard Visualizations

The dashboard features four main visualizations:

![image](https://github.com/user-attachments/assets/47344115-d181-4df6-8d10-59967e61547f)

### 1. Sales by Region (Bar Chart)

- **Type**: Bar Chart
- **Purpose**: Compares total sales performance across geographical regions.
- **Insights**: Identifies high and low-performing regions and regional sales disparities.
- **Interaction**: *(If implemented)* Allows drilling down or filtering by time periods.

### 2. Profit Margin by Category (Scatter Plot)

- **Type**: Scatter Plot
- **Purpose**: Shows the relationship between profit margin and product categories.
- **Insights**: Helps identify high-margin/high-profit categories and underperforming ones.
- **Interaction**: *(If implemented)* Reveals sub-category details or filters by region.

### 3. Shipping Cost Analysis (Line Chart)

- **Type**: Line Chart
- **Purpose**: Visualizes trends in shipping costs, typically over time or by shipping mode.
- **Insights**: Helps identify cost trends, key cost drivers, and efficiency opportunities.
- **Interaction**: *(If implemented)* Allows adjustment of time granularity or filtering by shipping modes.

### 4. Order Priority Breakdown (Pie Chart)

- **Type**: Pie Chart
- **Purpose**: Summarizes the distribution of orders by priority levels.
- **Insights**: Provides an understanding of urgency mix, operational load, and resource allocation needs.
- **Interaction**: *(If implemented)* Filters other dashboard elements based on selected priority.

## Future Enhancements

- Add "Sales over Time" line chart.
- Incorporate customer segmentation.
- Implement sales and profit forecast models.
- Include geographical maps.
- Add action filters.
