📈 Sales Data Mart Design Using AdventureWorks Database

This GitHub repository contains comprehensive documentation for a Sales Data Mart project. The objective of this project is to develop a robust data mart from the AdventureWorks database, encompassing fact tables for sales data and dimension tables for products, customers, time, and territories. Adopting a dimensional modeling approach, the project includes detailed processes for data extraction, transformation, and loading (ETL).

Data Model:

The data mart is structured with the following dimensional model:

Fact Sales: Contains sales-related measures and foreign keys linking to dimensions.

Dim Product: Stores detailed product information, including attributes such as product name, category, and subcategory.

Dim Customer: Includes comprehensive customer details and supports Slowly Changing Dimension (SCD) processing to manage customer changes.

Dim Time: Represents various time-related information, including date, month, quarter, and year.

Dim Territory: Contains territory information with attributes such as region, country, and state.

This project ensures an accurate and reliable data mart, facilitating advanced analytics and informed decision-making.
![Screenshot 2024-05-29 203558](https://github.com/A7med-3laa227/Sales_Data_Mart/assets/86737077/d66107df-41e1-488d-b72e-858546930547)

ETL Process Overview:

Dim Product Design:

Extract: Retrieve product data from the source database.
Transform: Cleanse and standardize product attributes such as name, category, and subcategory.
Load: Populate the Dim Product table with the transformed data.
Dim Customer Design:

Extract: Retrieve customer data from the source database.
Transform: Apply Slowly Changing Dimension (SCD) processing to manage customer changes, and cleanse customer attributes such as name and address.
Load: Populate the Dim Customer table with the transformed data.
Dim Time Design:

Extract, Transform, and Load: Populate the Dim Time table with time-related information, including dates, months, quarters, and years.
Dim Territory Design:

Extract: Retrieve territory data from the source database.
Transform: Cleanse and standardize territory attributes such as region, country, and state.
Load: Populate the Dim Territory table with the transformed data.
Fact Sales Design:

Extract: Retrieve sales-related data from the source database.
Transform: Perform necessary data transformations, including calculating measures and applying business rules.
Map: Ensure that foreign keys to dimension tables are accurately mapped.
Load: Populate the Fact Sales table with sales measures and the appropriate dimension keys.
This ETL process ensures that the data mart is populated with accurate, cleansed, and well-structured data, supporting comprehensive analytics and reporting capabilities.






