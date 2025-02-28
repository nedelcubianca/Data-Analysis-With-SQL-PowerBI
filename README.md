

# SQL and Power BI Integration Project

This project focuses on the normalization of a database and its visualization using Power BI. The goal was to transform an existing database into a well-structured format by applying normalization principles up to the Third Normal Form (3NF). The normalized database was then visualized using Power BI to create insightful reports and dashboards.

## Project Overview

### Database Normalization
The initial database contained redundant information and anomalies. To address these issues, the database was decomposed into multiple tables, each with a clear and specific structure. The normalization process resulted in six tables:
1. **Orders**
2. **Customers**
3. **Products**
4. **Order Details**
5. **Shipping**
6. **Shipping Methods**

### Power BI Visualization
After normalizing the database, the data was imported into Power BI to create interactive visualizations. The following key insights were derived from the data:
- **Profit Analysis**: A table showing orders with profits exceeding 5000 monetary units.
- **Customer Segmentation**: A bar chart illustrating the distribution of customers across different segments (Corporate, Home Office, Consumer, Small Business).
- **Product Category Distribution**: A donut chart showing the proportion of products sold in each category (Office Supplies, Technology, Furniture).

### SQL Queries and Analysis
Several SQL queries were performed to analyze the data, including:
- Finding customers who placed orders exceeding 1000 monetary units.
- Identifying the customer with the highest total order value.
- Filtering orders based on specific shipping methods and costs.
- Calculating the total profit for each shipping method.

### PL/SQL Procedures and Triggers
The project also included the creation of PL/SQL procedures and triggers to automate tasks such as:
- Updating shipping costs for specific shipping methods.
- Calculating the average profit across all orders.
- Validating that the profit in the Orders table cannot be negative.
- Auditing price changes in the Products table.

## Repository Structure
- **SQL Scripts**: Contains the DDL and DML scripts used to create and populate the database tables.
- **Power BI Reports**: Includes the Power BI files used to generate the visualizations.
- **Documentation**: Contains the project documentation, including the conceptual schema and normalization steps.

## Technologies Used
- **SQL**: For database normalization, querying, and analysis.
- **Power BI**: For data visualization and reporting.
- **PL/SQL**: For creating procedures and triggers to automate database tasks.
