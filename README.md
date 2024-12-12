# Tableau Sales and Customer Dashboards

This project involves the creation of two interactive Tableau dashboards: one for analyzing **sales performance** and another for understanding **customer behaviors and trends**. The dashboards are designed to provide stakeholders—including sales managers, executives, and marketing teams—with the necessary tools to make informed decisions based on historical sales and customer data.

## Table of Contents

- [Overview](#overview)
- [Sales Dashboard Requirements](#sales-dashboard-requirements)
  - [KPI Overview](#kpi-overview)
  - [Sales Trends](#sales-trends)
  - [Product Subcategory Comparison](#product-subcategory-comparison)
  - [Weekly Trends for Sales & Profit](#weekly-trends-for-sales--profit)
- [Customer Dashboard Requirements](#customer-dashboard-requirements)
  - [KPI Overview](#kpi-overview-1)
  - [Customer Trends](#customer-trends)
  - [Customer Distribution by Number of Orders](#customer-distribution-by-number-of-orders)
  - [Top 10 Customers By Profit](#top-10-customers-by-profit)
- [Design & Interactivity Requirements](#design--interactivity-requirements)
- [Data Filters](#data-filters)
- [Installation & Setup](#installation--setup)


## Overview

This project consists of two interactive Tableau dashboards designed for analyzing **sales performance** and **customer behavior**. The dashboards are aimed at two primary user groups:

- **Sales Managers and Executives**: Focus on sales performance metrics and trends.
- **Marketing Teams and Management**: Focus on customer trends, segments, and satisfaction.

Each dashboard is dynamic and allows stakeholders to filter and explore historical data in an intuitive and user-friendly manner. The dashboards include various KPIs, trends, and comparative analysis to provide deep insights into business performance.

---

## Sales Dashboard Requirements

### KPI Overview
- Display **total sales**, **profits**, and **quantity** for the current year and the previous year.

### Sales Trends
- Present monthly sales, profit, and quantity for both the current year and the previous year.
- Highlight months with the highest and lowest sales for easy identification.

### Product Subcategory Comparison
- Compare sales and profit by product subcategory for the current year and the previous year.
- Include both sales and profit in the comparison.

### Weekly Trends for Sales & Profit
- Display **weekly sales** and **profit** data for the current year.
- Show **average weekly values** for comparison.
- Highlight weeks above and below the average to emphasize performance differences.

---

## Customer Dashboard Requirements

### KPI Overview
- Display total **number of customers**, **total sales per customer**, and **total number of orders** for both the current year and the previous year.

### Customer Trends
- Present customer-related KPIs (e.g., sales, orders) on a monthly basis for both the current year and the previous year.
- Identify months with highest and lowest customer sales.

### Customer Distribution by Number of Orders
- Represent customer behavior by the number of orders they have placed.
- Provide insights into customer loyalty, engagement, and buying patterns.

### Top 10 Customers By Profit
- Display the **top 10 customers by profit**, with additional details such as **rank**, **number of orders**, **current sales**, **current profit**, and **last order date**.

---

## Design & Interactivity Requirements

- **Dynamic Dashboards**: Allow users to select any desired year to explore historical data.
- **Navigation**: Provide easy navigation between the Sales Dashboard and the Customer Dashboard for seamless exploration.
- **Interactive Charts**: Enable users to filter data directly from charts. For example, users can click on a bar chart to filter data by product, region, or year.
- **Visual Highlights**: Use color coding or other visual elements to highlight key metrics, such as the highest and lowest months for sales or profits.

---

## Data Filters

- Allow users to filter data by the following categories:
  - **Product Information**: Category, Subcategory.
  - **Location Information**: Region, State, City.

These filters enable users to drill down into specific subsets of data and gain more granular insights.

---

## Installation & Setup

To view the Tableau dashboards, follow these steps:

1. **Install Tableau Desktop**: You will need Tableau Desktop to open and interact with the Tableau workbook.
   - [Download Tableau Desktop](https://www.tableau.com/products/desktop)

2. **Clone the Repository**: Clone this GitHub repository to your local machine.
   ```bash
   git clone https://github.com/your-username/tableau-sales-customer-dashboards.git
