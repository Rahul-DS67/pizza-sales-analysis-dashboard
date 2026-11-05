# 📖 Data Dictionary — Pizza Sales Analysis

## 1. Overview

This document describes the fields used in the Pizza Sales Analysis project, including their meanings, expected data types, and analytical applications.

The data dictionary provides a reference for understanding the transactional dataset and its use in Power BI reporting.

## 2. Field Definitions

| Field Name | Data Type | Description | Analytical Usage |
|---|---|---|---|
| order_id | Whole Number | Identifier associated with an order | Order counting and transaction analysis |
| order_date | Date | Date when the order was placed | Daily, monthly, and quarterly trends |
| order_time | Time | Time when the order was placed | Hourly sales and peak-hour analysis |
| pizza_name | Text | Name of the pizza product | Product performance analysis |
| pizza_category | Text | Category to which the pizza belongs | Category-wise sales comparison |
| pizza_size | Text | Size of the pizza | Size-wise sales analysis |
| quantity | Whole Number | Number of pizzas ordered in a transaction line | Total quantity sold |
| unit_price | Decimal Number | Selling price of one pizza | Price analysis |
| total_price | Decimal Number | Total sales amount for a transaction line | Revenue calculations |

*Note: Data types represent the expected analytical types. Actual Power BI data types should be checked against the imported source.*

## 3. Business Interpretation

### Order Information
- **order_id:** Helps identify and count customer orders. Multiple pizza products may belong to the same order.
- **order_date:** Supports analysis of sales performance over different time periods.
- **order_time:** Helps identify peak ordering hours and demand patterns.

### Product Information
- **pizza_name:** Identifies individual pizza products for ranking and performance comparison.
- **pizza_category:** Enables category-level sales analysis.
- **pizza_size:** Helps evaluate sales distribution across different pizza sizes.

### Sales Information
- **quantity:** Represents the number of pizzas sold.
- **unit_price:** Represents the selling price per individual pizza.
- **total_price:** Represents the sales amount for the corresponding transaction line.

## 4. Key Analytical Measures

The following measures are used to evaluate sales performance:

| KPI | Description |
|---|---|
| Total Revenue | Sum of total_price |
| Total Orders | Distinct count of order_id |
| Total Pizzas Sold | Sum of quantity |
| Average Order Value | Total Revenue / Total Orders |

## 5. Derived Time Attributes

| Attribute | Description |
|---|---|
| Order Day | Day of the week derived from order_date |
| Month Name | Month name derived from order_date |
| Month Number | Numeric month value used for chronological sorting |
| Quarter | Financial/calendar quarter classification based on the analysis |
| Order Hour | Hour extracted from order_time |

## 6. Important Data Considerations

- An order may contain multiple pizza products.
- Order count should use distinct order IDs rather than counting transaction rows.
- Total pizzas sold should be calculated using the quantity field.
- Revenue should be aggregated using total_price.
- Average Order Value should be calculated using total revenue divided by distinct orders.
- Month names should be sorted using Month Number to maintain the correct chronological sequence.

---

**Project:** Pizza Sales Analysis Dashboard  
**Primary Tool:** Power BI  
**Supporting Tools:** Power Query and DAX
