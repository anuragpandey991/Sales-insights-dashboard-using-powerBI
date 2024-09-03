# Sales-insights-dashboard-using-powerBI
Sales Analysis Power BI Project

## Project Description
Integrated and cleaned data from 4 sources with 8,000+ orders, enabling year-over-year sales, profit, and margin analysis | Created interactive PowerBI visualizations (line, area, bar, pie charts) for product, customer, and regional insights | Implemented slicers for dynamic filtering, improving user experience and enhancing data-driven decision-making.

## Overview
This Power BI project aims to analyze sales data and provide insights into various aspects of sales performance. The project involves cleaning and integrating data from multiple sources to create a comprehensive analysis dashboard. Users can interact with the dashboard using slicers to filter data based on different criteria such as year, city, product name, and channels.

## Data Files
Sales Orders: Contains information on orders including order number, dates, customer details, product details, quantities, and pricing.
Customers: Provides customer index and names.
Regions: Includes geographic information such as suburbs, city, postcode, longitude, latitude, and full address.
Products: Lists product index and names.

## Project Steps
Data Cleaning: Removed unnecessary columns, handled blank values, and added additional columns for sales value, profits, profit margins, etc.
Data Integration: Connected all files with common columns to the sales orders file using Power BI's model view. Merge queries were used to incorporate relevant information from other documents into the sales order table.
Dashboard Interaction: Implemented slicers for year, city, product name, and channels to enable users to filter data according to their requirements.
Dynamic Dashboard: Implemented dynamic features where selecting a particular year compares it with the previous year. Extensive experimentation and reference to Microsoft documentation were carried out to achieve this functionality.
Visualization: Created various charts including line area chart for sales by product name, line chart for sales per month, bar chart for sales value by customer names, and pie chart for sales by region city, profits by distribution channels. All metrics are compared between the current and previous year.

## How to Use
Download: Clone or download the repository to your local machine.
Open: Open the Power BI project file (.pbix) using Power BI Desktop.
Refresh Data: If necessary, refresh data sources to ensure the latest information is reflected.
Interact with Dashboard: Use slicers to filter data based on your requirements. Explore different visualizations to gain insights into sales performance.
Feedback: Feel free to provide feedback or suggestions for improvement.

## Author
Anurag Pandey
