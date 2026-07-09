# **Big-Data-Insights**

# **Project Overview**
This project analyzes retail sales data using Power BI to uncover insights into sales performance, customer behavior, product performance, and country-wise sales trends. Interactive dashboards were created to help stakeholders monitor key business metrics and support data-driven decision-making.

# **Project Objectives**
- Analyze overall sales performance.
- Identify top-performing products.
- Understand customer purchasing behavior using RFM Analysis.
- Analyze country-wise sales performance.
- Create interactive dashboards for business decision-making.

# **Dataset Info**
Dataset: Online Retail II
The dataset contains transactional retail sales data with the following fields:
- Invoice
- Invoice Date
- Stock Code
- Description
- Quantity
- Price
- Customer ID
- Country

# **Data Cleaning**
The following transformations were performed using Power Query:

- Removed cancelled invoices.
- Removed blanks.
- Corrected data types.
- Created Revenue column.
- Created Date Table.
- Created Customer Table.


# **Data modeling**
The project follows a relational data model.

Tables:

- Online Retail
- Date Table
- Customers Table

Relationships were established between the tables to support time intelligence and customer analysis.

# **DAX Measures**

Some of the measures created include:

- Total Revenue
- Total Orders
- Total Customers
- Total Quantity
- Average Revenue per Customer
- Snapshot Date
- Revenue

# **Dashboard**

### Executive Dashboard

Provides an overview of business performance through KPI cards and revenue trends.

### Customer Dashboard

Analyzes customer behavior using RFM Analysis and customer segmentation.

### Product Dashboard

Highlights top-performing products, product revenue, and quantity sold.

### Country Dashboard

Analyzes revenue, customers, and orders across different countries.

# **Business questions**
- Which products generate the highest revenue?
- Which customers contribute the most revenue?
- Which countries perform best?
- How do sales change over time?
- How are customers segmented using RFM Analysis?

# **Key Insights**
- United Kingdom generated the highest revenue.
- Revenue peaked during November.
- Champion customers generated the highest customer value.
- A few products contributed a large share of total revenue.
- Sales performance varied across countries.

# **Tools Used**
 -Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
- # **Repository Structuer**
  
Retail-Sales-Analysis/

Dataset:https://docs.google.com/spreadsheets/d/1KG02zMfGBRxlaOEm9uAulOqiRrnKupZd/edit?usp=sharing&ouid=114041052825347382033&rtpof=true&sd=true

PDF Report: (https://docs.google.com/document/d/19QymRV7SzcUoSQz3ErqOuTVPCreGyriB/edit?usp=sharing&ouid=114041052825347382033&rtpof=true&sd=true)


# **Conclusion**

This project demonstrates the use of Power BI for transforming raw retail sales data into interactive dashboards that provide meaningful business insights for sales, customers, products, and country performance.
