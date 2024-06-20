# Mobile-Sales-Data-Analytics-using-Tableau
Mobile Sales Data Tableau project is a comprehensive dashboard for operational insights. It integrated 2015 sales data into interactive visualizations, including customer value, product sales, and sales rep performance. The project enhanced decision-making through detailed charts and KPIs, offering a clear view of business operations.


# Project Overview
The goal of this project was to create an interactive and comprehensive Tableau dashboard for Mobile Gadget Gurus, a distributor of mobile technology devices. The dashboard was designed to provide operational managers with insights into the company's sales, customer performance, product performance, and sales representative efficiency. The data used for this analysis covered the operational period of 2015.

The project was divided into three main parts:

Data Import and Preparation: This involved importing data from various tables and joining them in Tableau to create a cohesive dataset for analysis.
Dashboard Design and Visualization: This stage focused on designing and implementing four key dashboard pages – Home, Customer, Product, and Sales Rep.
Finalization and Presentation: The final part involved refining the dashboards and adding advanced features like KPIs and running totals to enhance the insights provided.
Data Import and Preparation
Data Source: The primary data source for this project was the 'Production Database' provided in Excel format. This database included several tables such as Sales and Profit, Customer, Product, and Sales Rep.
Data Import: The data was imported into Tableau by connecting to the Excel file and joining the tables based on relevant keys. Specifically:
The SALE AND PROFIT table was joined with the CUSTOMER table using Customer ID.
The PRODUCT table was joined with the SALE AND PROFIT table using Product ID.
The SALESREP table was joined with the SALE AND PROFIT table using Salesrep ID.
Dashboard Design and Visualization
The dashboard was designed to be user-friendly and provide critical insights through various visualizations. The design consisted of four main pages:

1. Home Page
The Home page served as the main interface, summarizing key performance indicators (KPIs) and providing an overview of the most critical metrics.

Key Visualizations:
Customer Lifetime Value: A bubble chart showcasing the lifetime value of top customers.
Order Frequency: A line chart displaying average order values over time.
Sales per Customer: A bar chart illustrating sales figures for different customers.

2. Customer Page
This page focused on customer-specific insights, helping managers understand which customers contribute the most to sales and profits.

Key Visualizations:
Customer Sales by State: A bar chart showing total sales per state.
Sales by Customer City: A map visualizing sales distribution across different cities.
Sales & Profit by Customer: A combined bar and box plot to compare sales and profit by customer.

3. Product Page
The Product page provided detailed insights into product performance, helping managers identify top-performing and underperforming products.

Key Visualizations:
Product Cost by Product: A bar chart representing the total cost of each product.
Sales & Profit by Product: A dual-axis chart showing both sales and profit margins for each product.
Qty on Hand by Product: A treemap displaying the quantity of products on hand.

4. Sales Rep Page
This page offered insights into the performance of sales representatives, highlighting their sales achievements and customer interactions.

Key Visualizations:
Sales Rep Benchmark: A bar chart comparing sales reps' performance against a benchmark.
Product Sales by Customer: A detailed bar chart showing the sales figures by each sales rep for different customers.
Sales & Profit by Customer for Sales Reps: A detailed breakdown of sales and profit data for each sales rep by customer.

Advanced Features and Finalization
To enhance the dashboards further, advanced features such as KPIs and running totals were added. These included:

Order Profit Percentage: A calculated field to determine the profit percentage for each order, displayed as a highlight table.
KPI Indicators: Created to show which orders were above or below a certain profit benchmark.
Running Totals: Implemented to track cumulative sales over time, providing a clear view of sales trends.
These features provided deeper insights and allowed for more dynamic analysis, enabling managers to make informed decisions based on the data visualized in the dashboards.

# Conclusion
The final Tableau dashboards provided Mobile Gadget Gurus with a powerful tool to monitor and analyze their operations. The visualizations allowed for easy tracking of sales performance, customer value, product efficiency, and sales rep effectiveness. This project demonstrated the capability of Tableau to transform raw data into actionable insights, supporting data-driven decision-making processes within the organization.
