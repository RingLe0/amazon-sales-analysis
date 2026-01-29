# Amazon Sales Data Cleaning and Analysis

## Overview
This project focuses on cleaning and analyzing an Amazon sales dataset to understand
sales volume, demand stability, and relationships between price, rating, and sales quantity.
The goal is to demonstrate practical data cleaning, exploratory data analysis (EDA),
and business-oriented insights.

## Data
- Source: Amazon sales transaction dataset
- Type: Transaction-level sales data
- Key variables:
  - productcategory
  - orderdate
  - quantitysold
  - unitprice

## Methods
- Data cleaning and preprocessing
- Aggregation of sales data by month and category
- Volume analysis (total units sold)
- Stability analysis using Coefficient of Variation (CV)
- Correlation analysis between price, rating, and quantity sold
- Data visualization using ggplot2

## Key Analysis
- Identified top-selling product categories based on total sales volume
- Measured demand volatility across categories using CV
- Explored price sensitivity through correlation and regression visualization
- Examined the relationship between customer ratings and sales distribution

## Results & Insights
- Some categories consistently drive the majority of total sales
- High CV categories show unstable demand and may require flexible inventory strategies
- Sales volume tends to decrease as unit price increases
- Higher product ratings are associated with higher sales quantities

## Tools
- R
- tidyverse
- ggplot2

## Files
- `Amazon-Sales-Data-Cleaning-and-Analysis.pptx`: Project presentation with analysis and visualizations

## Notes
This project emphasizes translating data analysis results into interpretable
business insights rather than predictive modeling.
