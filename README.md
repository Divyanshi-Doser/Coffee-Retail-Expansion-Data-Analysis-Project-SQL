# Coffee Retail Expansion Data Analysis Project

## Overview

This project focuses on analyzing customer, product, sales, and city data to identify the **top 3 cities for expanding coffee retail outlets** in India. The goal was to support business decisions using data-driven insights.

As a Data Analyst, I built a robust SQL-based data pipeline that handled:
- Data loading from CSV files
- Cleaning and transforming raw data
- Writing analytical queries to solve specific business problems

## Objectives

- Estimate potential coffee consumers in each city (25% of population)
- Analyze total revenue by city for Q4 2023
- Identify top-selling products in each city
- Compare average sales per customer with average rent
- Track monthly sales growth
- Recommend the best cities for market expansion based on multiple business metrics

## Dataset Structure

The project uses four CSV files:

1. `sales.csv` – Transaction data (sale ID, date, product ID, customer ID, total, rating)
2. `customers.csv` – Customer info linked to city
3. `products.csv` – Product names and prices
4. `city.csv` – City details including population, estimated rent, and rank

## Tools Used

- **SQL (PostgreSQL)** – For data cleaning, joins, aggregations, and business logic
- **Excel/Google Sheets** – For quick review or summary (optional)
- **Power BI / Tableau** – For creating dashboards (optional)
- **Markdown / GitHub** – For documentation and version control

## Key Insights

- **Pune**
  - Highest total revenue
  - Lowest average rent per customer
  - Strong average sales per customer

- **Chennai**
  - Second-highest revenue and average sales
  - Low rent per customer

- **Bangalore**
  - Balanced metrics
  - Third-highest performance across key indicators

- **Overall**
  - Monthly sales trend in Q4 2023 shows positive growth
  - Top 3 selling products vary by city

## Business Recommendation

Based on sales volume, rent efficiency, customer engagement, and estimated market size, the **top 3 cities for expansion** are:

1. **Pune**
2. **Chennai**
3. **Bangalore**

These cities show the most promising combination of demand, affordability, and profitability.


## Getting Started

1. Load the provided `.csv` files into a PostgreSQL database (if available).
2. Run the SQL scripts from the `coffee_expansion_queries.sql` file to generate insights.
3. Refer to the `schema.png` file for understanding the database design.
4. View the `Coffee_Expansion_Presentation.pdf` for the summarized report.

## Author

**Your Name**  
*Data Analyst | SQL | Business Intelligence*  
Email: your.email@example.com  
LinkedIn: [Your LinkedIn Profile]
