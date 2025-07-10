# CREATE-A-SALES-DASHBOARD
Company: CodTech IT Solutions
Name: Ekagrha Bhatia
Intern ID: CITS0D807
Domain : power BI
Duration: 8 Weeks
Mentor: Neela Santosh

Power BI Sales Dashboard – Project Description
Project Objective:
The primary objective of this project is to build a comprehensive and interactive Sales Dashboard using Power BI by integrating data from at least two different sources. In this instance, an Excel-based dataset has been used to demonstrate the capability. However, this approach can be extended to include SQL Server or other databases as additional data sources. The dashboard is designed to help stakeholders analyze sales performance across multiple dimensions including year, state, country, customer, and territory.

Data Sources:
Excel File (Sales Data set.csv.xlsx):
This file contains transactional sales data with fields such as:

ORDERDATE – Date of each sale

SALES – Sale amount in currency

CUSTOMERNAME – Name of the customer

DEALSIZE – Size of the deal (e.g., Large, Medium)

CITY, STATE, COUNTRY – Location-based details

YEAR_ID – Financial year

TERRITORY – Geographic business division

(Optional/Extensible) SQL Server:
While not shown in this prototype, a SQL Server database can be easily integrated using Power BI's native connectors. This would allow larger-scale enterprise deployments with live or scheduled data refresh.

Dashboard Components and Visuals:
The Power BI dashboard includes a range of visualizations designed to offer both high-level overviews and granular insights:

KPI Card:
Displays the total sum of all sales transactions across the dataset, allowing for an immediate understanding of overall revenue.

Bar Chart – Sales by Year:
Shows the maximum sales achieved per year (YEAR_ID), useful for identifying trends over time.

Funnel Chart – Sales by State:
Represents sales performance across various states, helping identify top-performing regions.

Pie/Donut Charts:

Sales by Country: Provides a breakdown of total sales per country, with the USA being the dominant contributor.

Sales by Territory: Segregates sales across global business territories (NA, EMEA, APAC, Japan).

Slicers:
Interactive filters for CITY and DEALSIZE allow users to dynamically refine visual outputs based on their selection.

Customer Table:
Lists top customers and their corresponding deal sizes for easy reference.

Sales Transactions Table:
Shows individual sales records with date and sale amount for detailed analysis.

Features and Techniques Used:
Data Transformation using Power Query Editor for cleaning and shaping data.

DAX Measures for calculating KPIs and performing aggregations.

Data Modeling to establish relationships between various tables and fields.

Interactive Filters and Slicers to enable self-service exploration of data.

Intuitive UI with clear labeling, consistent formatting, and readable layouts for end users.

Outcome and Benefits:
This dashboard enables stakeholders, analysts, and managers to make data-driven decisions with ease. It provides a clear view of business performance and helps identify areas of growth, top customers, and key geographical markets. The visual nature of Power BI also makes the data more accessible to non-technical users.

The modular design ensures that this solution can be scaled further by integrating additional data sources, enabling scheduled refreshes, and deploying to Power BI Service for real-time insights and collaboration.

OUTPUT
<img width="1364" height="718" alt="Image" src="https://github.com/user-attachments/assets/85c6e4c2-218b-4888-aec8-b3a1c72f21d0" />
