# Sales Data Analysis Project

## Project Overview
This project focuses on analyzing sales data of a global company operating in both online and offline markets. The dataset includes three tables: sales events, product categories, and country details. The goal is to clean, process, and analyze the data to uncover actionable business insights.

### Key Objectives:
1. Perform comprehensive data cleaning and validation
2. Analyze sales performance across product categories, regions, and sales channels
3. Investigate order fulfillment efficiency
4. Identify temporal patterns and seasonality in sales

## Dataset Description
### 1. `events.csv`
Contains transactional data from 2012-2017 with 11 columns:
- `Order ID`: Unique order identifier
- `Order Date`: Date of purchase
- `Ship Date`: Date of shipment
- `Order Priority`: Priority level (H/M/L/C)
- `Country Code`: ISO country code
- `Product ID`: Product identifier
- `Sales Channel`: Online/Offline
- `Units Sold`: Quantity sold
- `Unit Price`: Price per unit
- `Unit Cost`: Cost per unit

### 2. `products.csv`
Product reference data:
- `Product ID`: Unique product identifier
- `Product Category`: Product classification

### 3. `countries.csv`
Geographical reference data:
- `Country Code`: ISO country code
- `Country Name`: Full country name
- `Region`: Geographical region
