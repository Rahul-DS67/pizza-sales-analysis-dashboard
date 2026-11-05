# 📂 Dataset Description — Pizza Sales Analysis

## 1. Dataset Overview

This project uses a transactional Pizza Sales dataset containing sales records from January 1, 2015, to December 31, 2015.

The dataset captures individual pizza order transactions, including order details, product information, quantities, and sales amounts.

It contains approximately **48,620 records** and provides a foundation for analyzing business performance, product demand, and customer ordering patterns.

## 2. Dataset Scope

| Attribute | Description |
|---|---|
| Business Domain | Food & Beverage / Restaurant |
| Industry | Pizza Retail |
| Period Covered | January – December 2015 |
| Approximate Records | 48,620 |
| Data Granularity | Pizza order-line transaction |
| Primary Analysis | Sales Performance |
| Secondary Analysis | Product and Time-Based Trends |

## 3. Data Fields

The dataset contains the following key attributes:

| Column Name | Description |
|---|---|
| order_id | Unique identifier associated with an order |
| order_date | Date on which the order was placed |
| order_time | Time at which the order was placed |
| pizza_name | Name of the pizza product |
| pizza_category | Category of the pizza |
| pizza_size | Size of the pizza |
| quantity | Number of pizzas ordered |
| unit_price | Selling price per pizza |
| total_price | Total sales amount for the corresponding order line |

## 4. Data Preparation

The source data was treated as clean at source. However, validation and preparation were performed before developing the dashboard.

Key preparation activities included:

- Checking column names and data types.
- Validating date and time fields.
- Checking for missing or null values.
- Reviewing consistency across product names, categories, and sizes.
- Validating quantity and pricing fields.
- Preparing time-based attributes for analytical reporting.

## 5. Derived Attributes

Additional attributes were created to support time-based analysis:

| Derived Attribute | Purpose |
|---|---|
| Order Day | Analyze sales by day of the week |
| Month Name | Display monthly sales trends |
| Month Number | Maintain chronological month sorting |
| Quarter | Compare quarterly performance |
| Order Hour | Identify peak ordering hours |

## 6. Dataset Limitations

The dataset primarily supports transactional sales analysis.

The following information is not directly available in the documented fields:

- Ingredient and operational costs.
- Product-level profit margins.
- Customer demographics.
- Customer-level purchase history.
- Inventory availability and stock movement.

Consequently, profitability, customer segmentation, and detailed inventory optimization require additional data sources.

## 7. Usage in This Project

The dataset was used to develop an interactive Power BI dashboard covering:

- Overall sales performance.
- Revenue and order KPIs.
- Product and category performance.
- Pizza size analysis.
- Daily, monthly, quarterly, and hourly sales trends.
- Business insights and recommendations.

**Note:** The original dataset is not included in this repository. This document provides its structure, scope, and role in the analytical project.
