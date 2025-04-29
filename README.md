# Bike Shop Sales Dashboard

This repository contains a Power BI project for analyzing sales data from a bike shop.  
The `.pbix` file covers data transformation, visualization, and business intelligence insights.

![BikeShop Logo](https://github.com/Abhishek199820/bike_shop/blob/main/TomanBikeShop.png)

## Project Overview

- **File Name:** `Bike_Shop.pbix`
- **Tool Used:** Microsoft Power BI
- **Focus Areas:**
  - Data Cleaning and Shaping
  - Revenue and Profit Analysis
  - Product and Category Breakdown
  - Customer Segmentation

## Data Preparation

Before building the dashboard, data was filtered and transformed using SQL:

- Combined records from two years (`bike_share_yr_0` and `bike_share_yr_1`) using `UNION ALL`.
- Joined the dataset with a `cost_table` to retrieve `price` and `COGS` based on the year.
- Calculated key financial metrics:
  - **Revenue** = Riders × Price
  - **Profit** = (Riders × Price) – COGS

This prepared data was then imported into Power BI for visualization and analysis.

## Dashboard Explanation

The dashboard presents a clear, interactive summary of bike shop performance.  
It includes:

- **Key Metrics:** Total Revenue, Total Orders, Average Order Value
- **Trend Analysis:** Line and column charts tracking monthly performance
- **Product Insights:** Top-selling bike models and categories
- **Customer Overview:** Segmentation based on region or demographics
- **Geographic Distribution:** Maps showing regional performance (if applicable)
- **Interactive Filters:** Slicers for product type, year, and location

The visuals allow users to drill down into specifics and identify growth opportunities.

## Key Features

- Interactive dashboard for data-driven decisions
- Yearly and Category-wise performance breakdown
- Customer and Regional segmentation
- Filters for flexible analysis

## How to Use

1. Download the `Bike_Shop.pbix` file from this repository.
2. Open it using Microsoft Power BI Desktop.
3. Interact with slicers, charts, and filters to explore insights.

## Screenshots

![BikeShop Dashboard](https://github.com/Abhishek199820/bike_shop/blob/main/BikeShop-Dashboard.png)

## Author

- **Your Name** (Replace this with your name)
- [LinkedIn Profile] (Optional)
