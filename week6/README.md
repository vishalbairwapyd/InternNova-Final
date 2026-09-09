# Superstore Sales & Profit Analysis Using Power BI

## 1. Project Title

**Superstore Sales & Profit Analysis Using Power BI**

## 2. Project Overview

This project analyzes the Superstore dataset using Microsoft Power BI. The analysis focuses on sales, profit, orders, customers, products, categories, segments, regions, and business trends.

The main objective is to transform raw sales data into meaningful visualizations and an interactive dashboard that can support business decision-making.

## 3. Problem Statement

The objective of this project is to analyze Superstore sales data and identify important business patterns, trends, high-performing areas, low-performing areas, and opportunities for improving profitability.

## 4. Dataset Description

The Superstore dataset is a retail sales dataset containing information about orders, customers, products, sales, quantity, discount, profit, categories, sub-categories, segments, and regions.

The dataset was inspected and prepared before performing exploratory data analysis and visualization.

## 5. Tools Used

- Microsoft Power BI
- Power Query
- DAX
- Git & GitHub

## 6. Data Cleaning and Preparation

The following data preparation activities were performed:

- Checked column names and data types.
- Checked for missing/empty values.
- Checked for errors in the dataset.
- Checked duplicate records using Order ID and Row ID.
- Verified that Quantity values were greater than zero.
- Checked Sales values for invalid values.
- Checked Discount values.
- Verified that Order Date was less than or equal to Ship Date.
- Reviewed unusual and negative Profit values.
- Retained valid negative-profit transactions because they represent genuine business situations rather than confirmed data errors.

After cleaning and validation, the dataset was prepared for analysis.

## 7. Exploratory Data Analysis (EDA)

EDA was performed in Power BI to understand the major patterns and relationships in the dataset.

The analysis included:

- Descriptive statistics
- Category-wise sales and profit analysis
- Regional analysis
- Segment analysis
- Sub-category analysis
- Product-level analysis
- Monthly sales and profit trends
- Sales-profit correlation analysis
- Outlier identification

## 8. Data Visualizations

The following visualizations were created:

- KPI Cards
- Sales by Category
- Profit by Category
- Sales & Profit by Region
- Sales & Profit Trend Over Time
- Sales vs Profit Scatter Plot
- Sales & Profit by Segment
- Sales & Profit by Sub-Category
- Top 10 Products by Sales
- Top 10 Products by Profit

## 9. Power BI Dashboard

### Page 1 – Overall Business Performance Dashboard

This page presents the overall business performance using KPI cards and visualizations for sales, profit, orders, customers, categories, regions, and time trends.

### Page 2 – Detailed Sales & Profit Analysis

This page provides detailed analysis of customer segments, product sub-categories, and top-performing products.

### Interactive Features

The dashboard includes slicers for:

- Region
- Product Category

These filters allow users to interactively explore the dashboard.

## 10. Key Insights

1. Technology is one of the strongest categories in terms of sales and profit.
2. The West region has the highest sales among the four regions.
3. The Consumer segment contributes the highest sales and profit.
4. Some sub-categories have negative or relatively low profit despite generating sales.
5. The analysis shows a moderate positive relationship between Sales and Profit, with a correlation of approximately 0.48.
6. A small number of products contribute significantly to overall sales and profitability.
7. Sales and profit fluctuate across different months, with stronger performance during some later months.

## 11. Business Recommendations

1. Investigate low-profit and negative-profit sub-categories and review their pricing, discounts, and costs.
2. Focus on high-performing products and the Consumer segment while developing strategies to improve weaker regions and segments.

## 12. Project Conclusion

This project demonstrates how Power BI can be used to transform raw retail sales data into meaningful business insights. The analysis identified important sales and profitability patterns across categories, regions, customer segments, sub-categories, and products.

The interactive dashboard makes it easier to monitor business performance and explore the data using filters. The findings can support data-driven decisions related to product performance, profitability, discounts, and regional growth.

## 13. Project Files

The repository contains:

- Dataset
- Power BI `.pbix` file
- Dashboard screenshots
- Project report
- README documentation
