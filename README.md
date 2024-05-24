# Business_Insights_360
Link to Live Interactive DashBoard: https://shorturl.at/cnbyT

**Project Overview**

**About AtliQ Hardware**
AtliQ Hardware is an Electronics Goods Manufacturing company having operations in various countries. Their business is growing rapidly over the years but they had a bitter experience in regards to their recent establishment in Latin America acquiring huge loss. This was due to their incorrect decision making which are taken relying on surveys they conducted, excel sheets and their intuitions.

Hence, the company prioritized on-boarding data analytics and to make data driven decisions through an analytics solution. My role in this project will be is to Build a reports and provide insights considering various departments such as Finance view, Sales view, Marketing view, Supply Chain, on top of these we will have an Executive View with overall picture of the business such that stakeholders can unlock insights and enable data driven decision making.

**Project Objective:** This project's primary objective is to bring clarity to the data analytics initiative's purpose and objectives. The resulting report will serve as a cornerstone for data-driven decision-making, addressing a myriad of questions about the company's performance. It represents a crucial step in not only surviving but thriving in the industry.

**Tech stacks**
SQL
PowerBi Desktop
Excel
DAX language
DAX studio (for optimizing the report)
Project charter file

**Dataset Understanding.**
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

**Dimension table** : It will have the static data like details of customer and products

**Fact table** : It will have the data about the transactions

**Dimension Tables**

**dim_customer**
75 distinct customers throughout the market
2 types of platforms: Brick & Mortar (Physical/offline store) and E-commerce (Online Store)
Three channels: Retailer, Direct, Distributors

**dim_market**
27 distinct markets (e.g., India, USA, Spain)
7 sub-zones
4 regions: APAC, EU, nan, LATAM

**dim_product**
Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage
14 different categories (e.g., Internal HDD, keyboard)
Different variants available for the same product

**Fact Tables**

**fact_forecast_monthly**
Used to forecast the customer’s need in advance, leading to higher customer satisfaction and reduced storage costs.
Renormalized by the data engineering team for analytical work.
Dates of the month replaced by the start date of the month.
Contains forecast quantities needed by the customer.

**fact_sales_monthly**

Similar to the fact_forecast_monthly table, but with actual sold quantities.

**Miscellaneous Data**
freight_cost: Details of travel cost and other costs for each market with fiscal year
gross_price: Details of gross prices with product code
manufacturing_cost: Details of manufacturing cost with product code and year
Pre_invoice_deductions: Details of pre-invoice deductions percentage for each customer with year
Post_invoice_deductions: Details of post-invoice deductions and other deductions
Note: The Database which has both fact and dimension tables, consists of more than 1.4 Million records of different products, customers, purchases, etc..

 **Import data to Power BI**
After exploring the data, we now connect and load the AtliQ's data from MySQL database to the Power BI.

Note: Excel/ CSV Files are also the other data source, where the Targets and Market Share data related informations are imported to Power BI.

**Data Modelling**
Data modeling is the foundation of the report. All visuals are built upon the data model. Poor data modeling can affect the overall performance of the report.

**After importing data into the Power BI, the following procedures are to be followed:**

Cleaning, formatting and transforming the data using power query
Establishing relationships among the tables, employing either Star Schema or the Snow Flake methodology.
Subsequently, conducting data validation against the benchmarks set by the stakeholders

**Task:**
As a Data Analyst generate insights through reports built considering different sections such as

Finance view
Sales view
Marketing view
Supply Chain
Executive View
such that stakeholders can unlock insights and enable data driven decision making.



**Data Model**

**Home Page**
![model](https://github.com/Sravanthi-Duddeti/Business_Insights_360/assets/128029018/5a14ee6a-6009-4d4f-8021-a415f6c11efd)

**Sales View**

![Home](https://github.com/Sravanthi-Duddeti/Business_Insights_360/assets/128029018/e5afcf6a-65c8-4c84-ba91-f38a310071fa)
**Finance View**

![Finance_View](https://github.com/Sravanthi-Duddeti/Business_Insights_360/assets/128029018/065ceafb-5fd8-42ff-9895-bb077cb1641c)

**Marketing View**

![Marketing](https://github.com/Sravanthi-Duddeti/Business_Insights_360/assets/128029018/90c8083a-4183-485b-9baf-c63ee3c9c563)

**Supply chain View**
![Supply_Chain](https://github.com/Sravanthi-Duddeti/Business_Insights_360/assets/128029018/89441cd7-32cd-48a2-97ff-8be59a334ae7)
**Executive View**
![Executive](https://github.com/Sravanthi-Duddeti/Business_Insights_360/assets/128029018/ac2d9399-3af8-46fd-b661-fd2fbf5d4751)


