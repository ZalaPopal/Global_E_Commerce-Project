# Global_E_Commerce-Project 
<br>

## Overview

The Global E-Commerce Sales Dashboard is a data analytics project designed to help users understand e-commerce sales performance across different countries and regions around the world.

The project provides valuable insights that can support business decision-making by analyzing sales performance, customer behavior, product trends, profitability, and regional performance. Through data analysis and visualization, users can better understand key business metrics and identify important patterns within the data.

The dashboard was developed using Python, Dash, and Plotly. It includes interactive charts, maps, and filters that allow users to explore sales data in a simple and effective way. These interactive features make it easier to identify trends, compare performance, and gain meaningful business insights.

Overall, the Global E-Commerce Sales Dashboard serves as a powerful tool for understanding e-commerce sales and provides a comprehensive view of how e-commerce businesses are performing across different markets.

<br>

## Project Goals

Analyze sales performance across different countries and regions.
Identify top-performing products and product categories.
Understand customer purchasing behavior through customer segment analysis.
Evaluate profitability and profit margins across different markets.
Explore sales trends and patterns over time.
Develop an interactive dashboard that allows users to easily explore and visualize the data.

<br>

## Dataset

The Global E-Commerce Sales dataset contains transactional records from multiple countries and regions, structured with the following key features:

- Order Date  
- Product Name  
- Product Category  
- Customer Segment  
- Country  
- Region  
- Quantity  
- Unit Price  
- Discount Percent  
- Total Sales  
- Shipping Cost  
- Profit  
- Profit Margin  
- Payment Method  

<br>

## Tools  

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Dash  
- Plotly Graph Objects  

<br>

## Project Workflow


### Feature Engineering

The dataset was imported into Python using a Pandas DataFrame for analysis and processing.
Missing values, duplicate records, and null values were identified and handled to improve data quality and ensure accurate results.
Data type corrections were performed, particularly for date-related columns, to support time-based analysis.
Additional date features such as Year, Month, and Quarter were extracted from the Order Date column to enable trend analysis over different time periods.


### Exploratory Data Analysis

Summary statistics were generated to better understand the distribution of key numerical variables.
Customer segment analysis was performed to identify the contribution of different customer groups to sales and profit.
Product category analysis was conducted to compare sales and profitability across categories.
Regional and country-level analyses were carried out to evaluate geographic sales performance.
Sales trends were examined using monthly and quarterly aggregations to identify patterns and seasonal changes.
Payment method analysis was performed to understand customer payment preferences.
Correlation analysis was used to explore relationships between sales, profit, quantity, shipping cost, and profit margin.
Top-selling products were identified based on order frequency and total sales.


### Visualization

Bar charts were used to compare sales, profit, and shipping costs across categories, regions, and countries.
Line charts were created to visualize monthly sales trends and quarterly profit trends over time.
Pie charts were used to show the distribution of customer segments and payment methods.
Scatter plots were developed to analyze relationships between sales, profit, and shipping costs.
A correlation heatmap was created to highlight relationships among key numerical variables.
Interactive geographic visualizations were used to display sales performance across different countries and regions.
Dashboard filters and interactive components were implemented to allow users to explore the data dynamically and gain deeper insights.

<br>

## Key Results

Certain product categories generated significantly higher sales and profit compared to others.
Customer purchasing behavior varied across different customer segments.
Some countries and regions consistently outperformed others in terms of revenue and profitability.
Sales and profit showed a strong positive relationship, indicating that higher sales generally led to higher profits.
Shipping costs varied across regions and had an impact on overall profitability.
Interactive visualizations made it easier to identify trends, patterns, and business opportunities within the dataset.

<br>

## Conclusion

The Global E-Commerce Sales Dashboard successfully transformed raw sales data into meaningful business insights through data analysis and interactive visualizations. The project provided a better understanding of customer behavior, product performance, sales trends, and regional profitability. By combining exploratory data analysis with an interactive dashboard, users can efficiently explore the data and make informed business decisions based on real-world sales performance.
