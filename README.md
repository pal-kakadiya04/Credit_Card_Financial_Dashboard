# Credit_Card_Financial_Dashboard
Power BI Dashboard for Credit Card and Customer Analysis

## About the Project

This project focuses on developing an **interactive Power BI dashboard** for analyzing **credit card transaction data**, using a combination of **PostgreSQL**, **Excel**, and **DAX queries**. 
The dashboard provides insightful visualizations of financial trends, customer behavior, and transaction patterns. 

### Key Features:
- **Data Integration**: Combines transaction data from **PostgreSQL** with structured information from **Excel** to create a unified analysis framework.
- **Interactive Visualizations**: Includes bar charts, trend analysis, and customer demographics for easy exploration and analysis.
- **Advanced Analytics**: Implements DAX measures to calculate key metrics like revenue, average transaction value, and customer segmentation.
- **Business Impact**: Delivers actionable insights for decision-making, optimizing revenue, and detecting potential fraud.

## Project Steps

### 1. **Data Collection**
   - Gather transaction data from the **PostgreSQL** database, which contains records such as transaction history, customer profiles, merchant categories, and revenue.
   - Supplement with **Excel** for additional structured data, like transaction categories or demographic details.

### 2. **Data Cleaning and Preprocessing**
   - Clean the PostgreSQL data using SQL queries to remove duplicates and normalize data formats.
   - Ensure data consistency between the Excel and PostgreSQL datasets to guarantee seamless integration.

### 3. **Data Integration**
   - Import both PostgreSQL and Excel data into **Power BI** using native connectors.
   - Merge the datasets to create a unified data model for analysis.

### 4. **Data Modeling**
   - Build a **star schema** in Power BI to organize and model the data effectively.
   - Define relationships between key tables, including transactions, customers, and merchant categories.

### 5. **DAX Queries and Measures**
   - Use **DAX (Data Analysis Expressions)** to create calculated fields and measures, including:
     - Total Revenue
     - Total Transactions Count
     - Average Transaction Value
     - Revenue by Merchant Category
     - Customer Segmentation Metrics (e.g., spending behavior, income levels)

### 6. **Dashboard Design**
   - Design an **interactive Power BI dashboard** featuring:
     - Bar charts and line charts to visualize revenue and transaction trends.
     - Slicers to filter data by transaction date, card category, and customer demographics.
     - Trend analysis over time for better understanding of spending behavior.

### 7. **Insight Extraction**
   - Analyze the dashboard to uncover insights such as:
     - Revenue trends across different periods and card categories.
     - Spending patterns of customers based on demographics and merchant categories.
     - Fraud detection by identifying unusual transaction trends.

### 8. **Validation and Testing**
   - Validate data accuracy and functionality, ensuring that all measures and visualizations provide correct insights.
   - Test the responsiveness and interactivity of the dashboard with various user filters.

### 9. **Documentation and Presentation**
   - Document the data sources, analysis, and the process.
   - Provide a comprehensive report explaining the key findings from the dashboard.

## Technologies Used
- **Power BI**: For data visualization and dashboard creation.
- **PostgreSQL**: For storing and managing transaction and customer data.
- **Excel**: For additional structured data and manual data handling.
- **DAX**: For advanced data analysis and measures in Power BI.

## Abstract

This project develops a **Credit Card Financial Dashboard** using **Power BI**, powered by data from **PostgreSQL** and **Excel**. By integrating transaction data and applying advanced DAX queries, the dashboard provides detailed insights into financial trends, card performance, and customer behavior. It helps in identifying spending patterns & optimizing revenue. The interactive and visually engaging dashboard serves as an essential tool for businesses to make data-driven decisions and improve their financial strategies.

## Insightful Features

- **Data Integration**: The system combines PostgreSQL data with Excel files to offer a comprehensive view of transaction trends and customer behavior.
- **Interactive Visualizations**: The dashboard includes intuitive graphs, charts, and slicers that allow users to explore the data based on different filters and dimensions.
- **DAX Measures**: Advanced DAX queries are used to calculate vital metrics, such as total revenue, customer segmentation, and revenue breakdown by merchant category.
- **Actionable Insights**: The insights provided help businesses understand their customer base, and optimize marketing strategies.

## Conclusion

This project provides a robust analytical tool for understanding and managing credit card financial data. By combining **Power BI**, **PostgreSQL**, and **Excel**, it allows users to gain insights into transaction trends, customer behaviors, and financial risks. This data-driven approach empowers businesses to make informed decisions, enhance customer engagement, and improve financial management.

