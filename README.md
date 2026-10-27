# 🍕 Pizza Sales Analysis Dashboard

An end-to-end data analytics project exploring pizza sales performance, product trends, ordering patterns, and business opportunities using **Power BI, DAX, and Power Query**.

## 📌 Project Overview

The Pizza Sales Analysis Dashboard transforms transactional sales data into meaningful business insights. It provides a structured view of revenue, order volume, product performance, and time-based sales patterns to help decision-makers understand what drives sales and where operational improvements may be possible.

This project demonstrates practical skills in data preparation, data modeling, analytical calculations, interactive visualization, and business-focused storytelling.

## 🎯 Business Objectives

- Evaluate overall sales performance using key performance indicators (KPIs).
- Identify the best- and worst-performing pizzas.
- Analyze daily, monthly, quarterly, and hourly sales patterns.
- Understand revenue contributions by pizza category and size.
- Identify peak ordering periods and potential opportunities for improvement.
- Translate analytical findings into practical, data-informed recommendations.

## 🛠️ Tools & Technologies

| Tool | Application |
|---|---|
| Power BI Desktop | Dashboard development and visualization |
| DAX | KPI measures and analytical calculations |
| Power Query (M) | Data transformation and preparation |
| Excel / CSV | Source data and data inspection |

## 📂 Dataset Overview

The project uses transactional pizza sales data containing order-level and product-level information.

**Key fields include:**

- Order ID
- Order Date
- Order Time
- Pizza Name
- Pizza Category
- Pizza Size
- Quantity
- Unit Price
- Total Price

The source data was treated as clean at source, but its structure, data types, missing values, categorical consistency, and numeric fields were validated before analysis.

> **Data availability:** The complete raw dataset and Power BI report file are not included in this public repository. Selected documentation, dashboard screenshots, and project presentation materials are provided to demonstrate the analytical workflow and outcomes.

## 🔄 Data Preparation & Modeling

### 1. Data Loading and Validation
- Imported the source CSV data into Power BI.
- Verified data types for dates, times, text, and numeric fields.
- Checked for missing values and potential inconsistencies.
- Validated quantity and pricing fields.

### 2. Data Transformation
- Standardized pizza names, categories, and sizes where required.
- Prepared date and time fields for analysis.
- Checked the consistency of key analytical fields.

### 3. Feature Engineering
Derived additional time-based attributes to support the analysis:

- Order Day
- Month Name
- Month Number for chronological sorting
- Quarter
- Hour of Order

### 4. Analytical Modeling
Developed DAX calculations and analytical views to evaluate revenue, orders, pizza quantities, average order value, and product performance.

## 📊 Dashboard Features

### 1. KPI Summary
- Total Revenue
- Total Orders
- Total Pizzas Sold
- Average Order Value

### 2. Time-Based Analysis
- Monthly sales trends
- Quarterly revenue comparison
- Daily sales patterns
- Hourly sales distribution

### 3. Product Performance
- Top- and bottom-performing pizzas
- Revenue by pizza category
- Revenue by pizza size

### 4. Interactive Filtering
The dashboard includes slicers for:

- Month
- Day
- Hour
- Category
- Size

Custom slicer buttons support switching between monthly, weekly, and hourly views to make time-based analysis more accessible.

## 🖼️ Dashboard Preview

### Overall Dashboard
![Pizza Sales Dashboard Overview](images/dashboard-overview.png)

### Sales Trends
![Pizza Sales Trends](images/sales-trends.png)

### Product Performance
![Pizza Product Performance](images/product-performance.png)

*Dashboard screenshots will be displayed here once the corresponding images are uploaded to the repository.*

## 🔍 Key Business Insights

The analysis highlighted several patterns:

- **Peak ordering periods:** Sales activity is concentrated around lunch and dinner hours.
- **Product performance:** Certain pizza categories and individual products outperform others.
- **Revenue concentration:** A relatively small group of pizzas contributes a substantial share of revenue, consistent with a Pareto-style pattern.
- **Operational considerations:** Demand varies by time, making shift allocation and inventory planning important areas to evaluate.

These findings help identify where management attention may be most valuable.

## 💡 Business Recommendations

Based on the observed sales patterns, the project proposes the following actions:

1. **Focus promotions:** Prioritize products with strong sales performance rather than frequently changing the menu.
2. **Use time-based offers:** Explore targeted promotions during lower-sales periods to improve demand distribution.
3. **Optimize inventory:** Give appropriate attention to high-demand pizza categories and sizes.
4. **Increase average order value:** Evaluate suitable combo offers and product pairings.
5. **Improve shift allocation:** Maintain staffing stability while considering demand patterns when planning shifts.

Recommendations should be evaluated alongside profit margins, ingredient availability, staffing constraints, and implementation costs before business decisions are made.

## 📈 Project Outcomes

- Developed a structured view of key sales performance indicators.
- Improved visibility into product and time-based sales patterns.
- Translated analytical findings into practical business recommendations.
- Demonstrated an end-to-end analytics workflow from data preparation to business communication.

## 🚀 Future Enhancements

- Add cost and profit-margin analysis.
- Introduce customer segmentation, where suitable customer-level data is available.
- Forecast future sales using time-series methods.
- Explore automated data refresh and scheduled reporting.
- Incorporate inventory and product availability data for deeper operational analysis.

## 📁 Repository Contents

- `images/` — Dashboard screenshots and visual previews.
- `documentation/` — Dataset overview and data dictionary.
- `presentation/` — Project presentation in PDF format.
- `README.md` — Project overview, methods, features, and business findings.

## 👤 About This Project

This project is part of my data analytics portfolio, demonstrating the use of Power BI, analytical thinking where applicable, data preparation, and business-oriented reporting.

**Focus areas:** Data Analytics · Power BI · DAX · Power Query · Data Visualization · Business Insights

