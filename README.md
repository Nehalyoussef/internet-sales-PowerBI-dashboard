# Sales Performance Dashboard (Power BI)
## Project Overview

This dashboard was created as a practice project while studying Power BI through the 365 Data Science platform.
The goal of the project is to analyze internet sales performance, customer distribution, and product trends using a structured star-schema dataset and interactive visualizations.

The dashboard provides a high-level business overview and helps answer questions related to:

* Total sales performance

* Products sold

* Customer distribution

* Sales breakdown by gender and country

## Dataset Description

The dataset used in this project is based on the AdventureWorks Internet Sales data model, which is a widely used sample dataset for learning business intelligence, data modeling, and analytics.

It simulates a real-world retail scenario where an international company sells products online across different regions, categories, and customer segments.

### Tables Used

The data follows a fact and dimension model:

### Fact Table

### fact_InternetSales

* Contains transactional sales data such as sales amount, order quantity, customer, product, date, and territory references.

### Dimension Tables

### dim_ProductCategory

* High-level product categories (e.g., Bikes, Accessories).

### dim_ProductSubCategory

* Subcategories linked to product categories.

### dim_Product

* Detailed product information.

### dim_SalesTerritory

* Sales regions and countries.

### dim_Currency

* Currency information for sales transactions.

### dim_Customer

* Customer demographic data including gender and location.

This structure makes the dataset ideal for Power BI modeling, DAX calculations, and business reporting.

## Dashboard Features

The dashboard includes the following key insights:

* Total Sales Amount

* Total Products Sold

* Total Number of Customers

* Products Sold by Gender (Male / Female split)

* Products Sold per Country

* Interactive filtering for better exploration of the data

## Dashboard Description
This dashboard presents an overview of an online retail business, highlighting how sales perform across customers, products, and countries.

At a high level, it provides an executive summary of total sales, products sold, and customer count, giving quick insight into overall business performance and reach.

Customer analysis shows an almost even split between male and female product purchases, indicating a balanced customer base. From a geographic perspective, the United States leads in product sales, followed by Australia and Canada, while European countries contribute a smaller yet meaningful share.

Overall, the dashboard converts sales data into actionable insights by showing who the customers are, where sales originate, and how performance varies across regions, supporting data-driven business decisions.

## Tools & Technologies

* Power BI

* DAX

* Data Modeling (Star Schema)

* 365 Data Science Learning Platform
