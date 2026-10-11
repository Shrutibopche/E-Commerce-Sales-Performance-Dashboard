# E-Commerce Sales Performance Dashboard

## Project Overview

This project analyzes e-commerce sales performance, customer contribution, product categories, discounts, and delivery performance using Python, Excel, and Power BI.

The project follows an end-to-end data analysis workflow, starting with data exploration and preparation in Python and ending with an interactive Power BI dashboard.

## Project Workflow

Raw E-Commerce Dataset  
↓  
Python – Data Cleaning, EDA & Feature Engineering  
↓  
Excel – Prepared Dataset  
↓  
Power BI – Data Visualization & Dashboard  
↓  
Business Insights & Recommendations

## Dataset

The project uses an E-Commerce Sales dataset containing information related to:

- Customers
- Orders
- Order dates
- Products
- Product categories
- Sales
- Quantity
- Discounts
- Customer ratings
- Delivery status
- Delivery days
- Cities

The dataset was first explored and analyzed using Python. After data cleaning and exploratory data analysis, the prepared data was loaded into Excel and then used as the data source for the Power BI dashboard.

## Tools & Technologies

### Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering

### Excel
- Data storage and preparation
- Data validation and review

### Power BI
- Data Visualization
- Interactive Dashboard
- KPI Cards
- Charts and Tables
- Slicers
- Business Analysis

## Dashboard KPIs

| KPI | Value |
|---|---:|
| Total Customers | 904 |
| Overall Discount | 20.7% |
| Average Customer Rating | 2.92 |
| Average Sales per Product | 1.92M |
| Overall Revenue | $9.15M |
| Total Quantity | 5K |
| Total Orders | 904 |
| Delivered Orders | 690 |
| Undelivered Orders | 214 |
| Average Delivery Days | 4 |
| Delivery Completion | 76% |

## Dashboard Features

The Power BI dashboard provides analysis of:

- Overall sales performance over time
- Revenue by product category
- Customer contribution to revenue
- Revenue contribution by city
- Discount bands and their effect on quantity and sales
- Delivery performance
- Delivery status
- Total orders by city
- Customer rating and delivery performance

### Interactive Filters

The dashboard includes filters for:

- Order Date
- City
- Product Category

These filters allow users to interactively explore different segments of the e-commerce data.

## Key Insights

- The business generated approximately **$9.15M in overall revenue**.
- **Electronics** generated the highest revenue among the product categories shown in the dashboard.
- **New York** was the highest-contributing city by total sales.
- The overall discount rate was approximately **20.7%**.
- The average customer rating was **2.92**.
- **690 out of 904 orders** were delivered, resulting in approximately **76% delivery completion**.
- The average delivery time was approximately **4 days**.
- The discount-band analysis helps evaluate how different discount levels relate to quantity sold and final sales.

## Business Recommendations

Based on the analysis:

- Focus on high-performing product categories such as Electronics while identifying opportunities to improve lower-performing categories.
- Investigate customer experience factors contributing to the relatively low average customer rating.
- Analyze undelivered orders to identify potential delivery issues and improve the delivery completion rate.
- Monitor discount strategies to identify discount levels that support sales without unnecessarily reducing revenue.
- Focus marketing and sales strategies on high-performing cities while identifying growth opportunities in lower-performing locations.
- Monitor sales trends over time to support inventory and promotional planning.

## Dashboard Preview

![E-Commerce Sales Performance Dashboard](Dashboard%20Preview.png)

## Project Files

| File | Description |
|---|---|
| `E-Commerce Sales Performance Dashboard.pbix` | Power BI dashboard file |
| `E-Commerce Dataset.xlsx` | Excel dataset used for the analysis |
| `Dashboard Preview.png` | Preview of the Power BI dashboard |
| `README.md` | Project documentation |

## Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, Excel, and Power BI.

Python was used for data cleaning, exploratory data analysis, and feature engineering. The prepared data was then organized in Excel and used in Power BI to build an interactive dashboard that transforms e-commerce data into actionable business insights.
