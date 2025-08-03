# Adventure-Works-Sales
This repository provides an industrystandard resource for data analysis and BI. It includes transactional data from a fictional company, Adventure Works  and is perfect for practicing skills with Power BI, Tableau, and SQL. The data model includes key fact and dimension tables for analyzing sales trends, products, customers, and territories.
This repository contains the AdventureWorks sales dataset, a rich, multi-dimensional dataset provided by Microsoft. The data simulates a fictional multinational manufacturing company, "Adventure Works," that sells bicycles and bicycle accessories. This dataset is an industry-standard resource widely used for learning, practicing, and demonstrating data analysis, business intelligence (BI), and data modeling skills.

The goal of this project is to provide a clean and structured dataset for in-depth sales performance analysis. This includes understanding sales trends, identifying top-performing products and customers, and gaining insights into regional and temporal sales patterns.

Dataset Description
The AdventureWorks sales data model is based on a data warehouse schema, which is optimized for reporting and analysis. It is typically comprised of several tables, including fact and dimension tables, that are linked together by relationships.
Key Tables and Data Points:

Fact Table : This is the central table containing all transactional data. It includes key metrics such as:

Sales Amount: Total revenue generated from each transaction.

Order Quantity: The number of units sold.

Unit Price: The price of a single unit.

Order Date, Due Date: Timestamps for a variety of sales-related events.

Foreign Keys: Links to other dimension tables (e.g., ProductKey, CustomerKey, SalesTerritoryKey).

Dimension Tables : These tables provide descriptive information that enriches the sales data. They typically include:

DimProduct: Detailed information about each product, including ProductName, ProductCategory, ProductSubcategory, ProductColor, etc.

DimCustomer: Demographic and geographic information about customers, such as FirstName, LastName, EmailAddress, City, StateProvinceName, and CountryRegionName.

DimSalesTerritory: Details about the sales territories, including SalesTerritoryName and SalesTerritoryGroup.

DimDate: A calendar table that provides temporal attributes like Year, Month, Quarter, Day, and FiscalYear, which are crucial for time-based analysis.
