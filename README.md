# E-Commerce Business Insights – SQL Analysis Project
# Overview

This project analyzes real-world e-commerce transaction data using SQL to uncover customer behavior, revenue distribution, and sales trends. The goal was to simulate a realistic business analytics workflow, including working with multiple related tables, debugging joins, and translating query results into business insights.

The analysis was conducted using SQLite and focuses on answering practical questions a business or stakeholder might ask.

## Dataset

The dataset contains transactional data split across multiple tables:

customers

orders

order_items

order_payments

order_reviews

These tables were joined using primary and foreign keys to perform relational analysis.

## Tools & Technologies

SQLite

DB Browser for SQLite

SQL (joins, aggregation, grouping, ordering)

GitHub for version control and documentation

## Key Business Questions & Analysis
### 1. Top Customers by Total Spend

This analysis identifies the customers who have generated the highest total payment value across all their orders.

Insight:

A small group of customers accounts for a disproportionately large share of total revenue, highlighting the importance of customer retention and loyalty strategies.

### 2. Revenue by Customer State
   
This query aggregates total revenue by customer state to understand geographic revenue distribution.

Insight:

Revenue is concentrated in a limited number of states, suggesting regional demand patterns that could inform marketing and logistics decisions.

### 3. Monthly Revenue Trend

This analysis tracks how revenue changes over time by aggregating payments by purchase month.

Insight:

Revenue shows clear fluctuations over time, indicating potential seasonality and periods of higher customer activity.

### 4. Revenue by Payment Method
   
This optional analysis explores how different payment methods contribute to total revenue.

Insight:

Certain payment methods dominate total transaction value, which may influence payment processing strategies and user experience decisions.

## Key Skills Demonstrated

Writing complex SQL joins across multiple tables

Debugging mismatched keys and empty join results

Aggregating and summarizing large datasets

Translating raw query results into business insights

Structuring and documenting an analysis project clearly

## Project Structure

analysis_queries.sql – final SQL queries used for analysis

business_insights.db – SQLite database

images/ – screenshots of query results

README.md – project documentation

## Conclusion

This project demonstrates practical SQL skills applied to real business questions. It emphasizes not only query writing, but also analytical thinking, data validation, and clear communication of insights.
