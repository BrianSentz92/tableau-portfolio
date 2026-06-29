# Customer Behavior Dashboard

## Overview

This project presents an interactive customer behavior dashboard built in Tableau to analyze purchasing patterns, customer engagement, and profitability across customer segments and product categories. The dashboard combines executive-level KPIs with behavioral analytics to help identify high-value customer segments and opportunities for improving customer performance.

---

## Dashboard Preview

![Customer Behavior Dashboard](images/dashboard.png)

---

## Use Case

This dashboard is designed for:

- Sales and marketing leaders evaluating customer purchasing behavior
- Business analysts identifying profitable customer segments
- Leadership teams monitoring customer engagement and revenue generation
- Customer success teams seeking opportunities to improve customer value

---

## Business Questions

This dashboard is built to answer the following questions:

- How large is the current customer base?
- How frequently do customers place orders?
- Which customer segments generate the highest revenue per customer?
- Which customer segments and product categories generate the highest average profit per order?
- Where are opportunities to improve customer profitability?

---

## Dashboard Metrics

The dashboard includes four executive KPIs:

- **Unique Customers**
- **Total Orders**
- **Average Orders per Customer**
- **Revenue per Customer**

These KPIs provide a high-level summary of customer activity and business performance.

---

## Dashboard Walkthrough

### KPI Summary

Provides an executive snapshot of customer activity by displaying the number of unique customers, total orders, average orders per customer, and average revenue generated per customer.

![KPI Summary](images/kpi.png)

---

### Customer Order Frequency Distribution

A histogram showing how often customers place orders. Most customers place between five and eight orders, helping identify the overall purchasing behavior of the customer base.

![Customer Frequency Distribution](images/histogram.png)

---

### Average Profit per Order by Segment and Category

A heatmap comparing average profit per order across customer segments and product categories. Darker blue cells represent higher average profit, while warmer colors indicate lower profitability.

![Profit Heatmap](images/heatmap.png)

---

### Average Revenue per Customer by Segment

A lollipop chart comparing average revenue generated per customer across Consumer, Corporate, and Home Office segments.

![Revenue per Segment](images/lollipop.png)

---

## Key Insights

This dashboard highlights several important customer behavior trends:

- Most customers place between five and eight orders, indicating a healthy level of repeat purchasing.
- Technology products generate the highest average profit per order across every customer segment.
- Furniture consistently produces the lowest average profit per order regardless of customer segment.
- Home Office customers generate the highest average profit per Technology order.
- Corporate customers generate the highest average revenue per customer.

These insights help identify which customer segments and product categories contribute the greatest business value.

---

## Dataset

The dashboard is built using transactional sales data containing:

- Order ID
- Customer Name
- Order Date
- Sales
- Profit
- Product Category
- Customer Segment
- Region

### Data Assumptions

- Each record represents one customer order.
- Profit is calculated as Sales minus Cost.
- Revenue per Customer is calculated as total revenue divided by unique customers.
- Average Orders per Customer is calculated as total orders divided by unique customers.
- Average Profit per Order is calculated at the transaction level.

---

## Tools Used

- Tableau Desktop
- Tableau Public
- Microsoft Excel (Data Preparation)
- GitHub

---

## Future Improvements

Potential enhancements include:

- Customer lifetime value (CLV) analysis
- Customer retention and churn metrics
- Cohort analysis for repeat purchasing behavior
- Geographic customer segmentation
- Live data source integration

---

## View the Dashboard

**Tableau Public:**  
[Customer Behavior Dashboard](https://public.tableau.com/app/profile/brian.sentz/viz/CustomerBehavior_17814434942120/Dashboard)
