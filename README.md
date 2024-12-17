# Olist eCommerce Analytics

## Project Overview
This project focuses on data cleaning, exploration, and analysis of the Olist e-commerce dataset. The goal is to derive actionable insights and trends related to sales performance, customer behavior, and product analysis using Python.

## About Olist
Olist is a Brazilian e-commerce platform that connects small and medium-sized sellers to major marketplaces. Olist provides tools for sellers to manage their operations efficiently, helping them reach a broader customer base across various channels.

## Dataset Context
The dataset used in this analysis originates from Olist's operational data and contains information about orders, customers, products, and sellers. The dataset includes:
- Order details: transaction data for customers and products.
- Customer and seller information: geolocation and behavior insights.
- Product catalog and reviews.
- Sales metrics and timelines.

The analysis primarily focuses on understanding sales trends, customer segmentation, and seller performance.

## Data Model
On Kaggle, she shared its data of 100k orders from 2016 to 2018. There are 8+1 datasets to play with and explore. The data model has been described in image below and it is organised and normalised for each category.

![Data Model](/Users/georgekas/EDA_Project/E-Commerce-Analysis/Data/HRhd2Y0.png)

## Tools and Libraries Used
The analysis and visualizations were performed using Python and the following libraries:

- **pandas**: Data manipulation and cleaning.
- **numpy**: Numerical computations.
- **matplotlib**: Basic data visualizations.
- **squarify**: Tree map visualizations.
- **fim**: Apriori and association rule analysis.
- **datetime**: Date and time manipulations.

## Data Cleaning
Data cleaning ensures the data is accurate, consistent, and ready for analysis. The key steps involved:
- Handling missing values.
- Correcting data types for date and time fields.
- Removing duplicate entries.
- Outlier detection and treatment.

## Exploratory Data Analysis (EDA)
The following analyses were performed:

1. **Monthly Sales Trend**:
   - Analyzed sales performance over time to identify trends.

2. **Top 10 Products by Sales**:
   - Identified the products with the highest sales volume.

3. **Top 5 Customer Cities by Sales**:
   - Explored customer location data to find the cities contributing the most to sales.

4. **Top 10 Sellers by Sales**:
   - Highlighted the sellers with the most significant sales contributions.

5. **RFM Analysis**:
   - Used Recency, Frequency, and Monetary analysis to segment customers based on purchasing behavior.

6. **Pareto Analysis**:
   - Performed Pareto analysis (80/20 rule) to understand the products or sellers driving the majority of the sales.

## Insights and Findings
The analysis revealed key insights such as:
- The concentration of sales across specific customer cities and sellers.
- Identification of high-performing products and their contribution to revenue.
- Customer segmentation using RFM analysis to target marketing efforts.
- Pareto analysis showcased that a small proportion of products drive the majority of sales.

## Conclusion
This project demonstrates the use of Python for cleaning, analyzing, and visualizing real-world e-commerce data. The findings can help Olist optimize its operations, target customers effectively, and improve seller performance.