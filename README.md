# Global-E-Commerce-Performance
This project analyzes global e-commerce data to uncover sales trends, profitability, customer behavior, and product performance. Data was cleaned and transformed using Excel and SQL, then explored through Power BI. The analysis identified top products, regional performance, and business opportunities to support smarter decisions and growth overall.
GLOBAL E-COMMERCE FINDINGS AND RECOMMENDATIONS
1. Introduction
The e-commerce industry has experienced significant growth, creating large volumes of transactional data that businesses can use to understand customer purchasing behavior, monitor sales performance, and improve business operations.
This project focuses on analyzing a Global E-Commerce dataset to evaluate the company's sales and profitability across different geographical regions, markets, product categories, and customer segments.
The project involves data cleaning and preparation using Microsoft Excel and SQL Server, followed by data analysis and visualization using Microsoft Power BI. The analysis focuses on key performance indicators (KPIs), including total sales, total profit, total orders, and average discount.
Interactive dashboards were developed to present important business insights, identify high-performing products and customers, examine monthly sales trends, and evaluate regional and category performance.
The overall aim of this project is to transform raw e-commerce data into meaningful insights that can help management make informed, data-driven business decisions. 
Problem Statement — Global E-Commerce Data Analysis
The global e-commerce business generates a large volume of sales transactions across different regions, markets, product categories, and customer segments. However, without proper analysis, it can be difficult for management to understand which products and markets contribute most to revenue and profitability.
The business needs to identify its top-performing products and customers, evaluate sales trends, compare regional and market performance, and investigate categories or sub-categories that generate low or negative profit.
Additionally, inconsistent data formats, missing values, duplicate records, and incorrect data types can affect the accuracy and reliability of business reporting.
This project addresses these challenges by cleaning and preparing the e-commerce dataset, analyzing key performance indicators using SQL and Excel, and developing an interactive Power BI dashboard to support data-driven business decisions.
Key Business Questions
1.	What are the company's total sales, total profit, total orders, and average discount?
2.	Which regions and markets generate the highest sales?
3.	Which product categories contribute most to sales and profit?
4.	Which products and customers generate the highest sales?
5.	How do sales change over time?
6.	Which sub-categories generate the highest and lowest profits?
7.	How do Consumer, Corporate, and Home Office segments contribute to sales?

2. Project Objectives
The main objective of this project is to analyze global e-commerce sales data and generate useful business insights through data cleaning, analysis, and visualization.
The specific objectives are:
1.	Clean and prepare the dataset: Identify and address data-quality issues, including missing values, inconsistent formatting, duplicate records, and incorrect data types.
2.	Analyze overall business performance: Calculate total sales, total profit, total orders, and average discount to understand the company's overall performance.
3.	Evaluate regional and market performance: Identify the geographical regions and markets generating the highest and lowest sales.
4.	Analyze product category performance: Compare sales and profitability across Technology, Furniture, and Office Supplies.
5.	Identify top-performing products: Determine the products contributing the most to total sales.
6.	Evaluate customer performance: Identify the highest-value customers and examine sales contributions across Consumer, Corporate, and Home Office segments.
7.	Examine sales trends: Analyze monthly sales patterns to identify fluctuations and potential seasonal trends.
8.	Assess sub-category profitability: Identify profitable and loss-making product sub-categories.
9.	Develop interactive dashboards: Use Power BI to create visual reports with KPI cards, charts, slicers, and interactive filters.
10.	Provide business recommendations: Use the findings to suggest ways to improve profitability, customer retention, sales performance, and business operations.
3. Data Description
The dataset used for this project is a Global E-Commerce transactional dataset containing information about customer orders, products, sales, shipping, and profitability across different markets and geographical regions.
The dataset is structured at the transaction or order-line level, meaning that individual records represent products associated with customer orders. An order may therefore appear in multiple rows when it contains multiple products.
The dataset contains the following main categories of information:
A. Order Information
•	Order ID
•	Order Date
•	Ship Date
•	Ship Mode
•	Order Priority
•	Year
These fields provide information about customer transactions, order timing, and shipping arrangements.
B. Customer Information
•	Customer Name
•	Segment
These fields help analyze customer purchasing behavior and compare performance across customer segments.
C. Geographical Information
•	State
•	Country
•	Market
•	Region
These fields support geographical analysis and comparisons of sales performance across different locations.
D. Product Information
•	Product ID
•	Category
•	Sub-Category
•	Product Name
These fields are used to identify top-selling products and evaluate the performance of different product categories and sub-categories.
E. Financial and Performance Information
•	Sales
•	Quantity
•	Discount
•	Profit
•	Shipping Cost
These numerical fields support calculations of revenue, profitability, order quantities, discount levels, and shipping expenses.
Tools Used
Tool	Purpose
Microsoft Excel	Initial data inspection, cleaning, and preparation
SQL Server	Data cleaning, duplicate checks, data validation, and querying
Microsoft Power BI	Data visualization, KPI reporting, and interactive dashboards
Dataset Usage
The dataset was used to develop three Power BI dashboard pages:
1.	Executive Overview — summarizes overall business performance.
2.	Sales Analysis — examines regional sales, market performance, category performance, and monthly trends.
3.	Products and Customer Analysis — evaluates top products, top customers, customer segments, and sub-category profitability.
The prepared dataset serves as the foundation for the analysis and visualizations presented in this project.
Data Cleaning and Preparation Process Using Excel
Before conducting the analysis, the Global E-Commerce dataset required data-quality checks and preparation to improve its consistency and reliability.
The following cleaning activities were used or identified during the data preparation process:
1. Data Importation
The original CSV dataset was imported into Excel for inspection and preparation.
2. Checking Missing and Blank Values
The dataset was examined for missing values, particularly in important fields such as Order ID, Customer Name, Order Date, and Product ID. Blank values were identified and assessed before analysis.
3. Removing Unnecessary Spaces
Text fields were checked for unwanted leading and trailing spaces. Excel's TRIM function can be used to standardize text values and prevent inconsistent grouping.
4. Duplicate Record Investigation
Duplicate records were investigated using Order ID, Product ID, and other transaction fields.
The checks distinguished between completely identical rows and records that shared some fields but contained different transaction details.  54 duplicates removed.
5. Date Formatting
Order Date and Ship Date were checked and standardized into consistent date formats to support time-based analysis.
6. Numeric Data Formatting
Sales, Profit, Quantity, Discount, and Shipping Cost were checked to ensure they were stored as numeric values rather than text. This supports accurate calculations and aggregations.
7. Handling Blank Text Values
Unnecessary blank strings and inconsistent text entries were identified. Blank values were standardized where appropriate without inventing missing customers or transaction information.
8. Data Validation
The prepared dataset was reviewed to confirm that the columns were consistent and suitable for analysis in SQL Server and Power BI.
Outcome
The data-preparation process produced a more consistent dataset for calculating sales and profit measures, analyzing customer and product performance, and developing interactive Power BI visualizations.
Dashboard Analysis Summary
The Global E-Commerce dashboard provides an overview of the company's sales performance, profitability, customer behavior, and product performance across different markets and regions.
The Executive Overview shows approximately $12.64 million in total sales, $1.47 million in total profit, and an average discount of 14.53%. It highlights the company's overall performance and compares sales and profit across product categories and geographical regions.
The Sales Analysis dashboard shows that the Central region generates the highest sales, while APAC is the leading market, followed by EU, US, and LATAM. Technology records the highest sales and profit among the three main product categories. The monthly sales trend also reveals fluctuations in sales throughout the year.
The Products and Customer Analysis dashboard identifies leading products, the top 10 customers, and the most profitable sub-categories. Smartphones and office equipment feature among the top-selling products, while Copiers, Phones, and Bookcases are among the strongest profit contributors. The analysis also highlights the importance of understanding customer segments and investigating sub-categories with negative profit.
Overall, the dashboard transforms the raw e-commerce dataset into meaningful visual insights that help management monitor business performance, identify profitable markets and products, understand customer contributions, and make informed decisions to improve sales and profitability.


Key Findings — Global E-Commerce Analysis
1.	Overall business performance: The dashboard reports approximately $12.64 million in total sales and $1.47 million in total profit, demonstrating that the business generates substantial revenue and positive overall profitability.
2.	Product category performance: Technology is the leading category by sales, followed by Furniture and Office Supplies. Technology also generates the highest profit among the three categories.
3.	Regional performance: Central is the strongest sales region in the dashboard, followed by South and North. This indicates that sales performance varies considerably across geographical regions.
4.	Market performance: APAC records the highest sales among the markets displayed, followed by EU, US, and LATAM. Canada contributes the least sales.
5.	Monthly sales patterns: Sales fluctuate across the months, indicating that demand is not consistent throughout the year. Further year-by-year analysis is needed to establish reliable seasonal patterns.
6.	Product performance: A small group of products, including smartphones and office equipment, accounts for a significant share of product sales.
7.	Customer performance: The Top 10 Customers visual demonstrates that some customers contribute more sales than others, providing an opportunity for customer retention and targeted marketing.
8.	Sub-category profitability: Copiers, Phones, and Bookcases are among the stronger profit contributors, while Tables shows a negative profit contribution and requires further investigation.
9.	Discount management: The average discount is approximately 14.53%. Management should investigate whether higher discounts are associated with lower profit margins.
Business Recommendations
Based on the findings from the Global E-Commerce dashboard, the following recommendations are proposed:
1. Strengthen High-Performing Markets
The business should maintain its presence in APAC, EU, US, and LATAM because these markets contribute significantly to total sales. Marketing strategies should be tailored to customer demand in each market.
2. Improve Furniture Profitability
Furniture generates substantial revenue but comparatively lower profit than Technology. Management should investigate product costs, discounts, shipping expenses, and pricing strategies within this category.
3. Investigate Loss-Making Sub-Categories
The negative profit contribution from Tables should be investigated. The business should review pricing, product costs, shipping expenses, and discount levels to identify the reasons for losses.
4. Strengthen Customer Retention
The business should develop loyalty programs, personalized promotions, and targeted marketing campaigns for its highest-value customers.
5. Optimize Discount Strategies
Management should evaluate the relationship between discounts and profit margins. Discounts should be applied strategically to encourage purchases without unnecessarily reducing profitability.
6. Improve Sales Forecasting
Historical monthly sales patterns should be monitored to support inventory planning, marketing campaigns, and demand forecasting.
7. Monitor Regional Performance
Regions with lower sales should be investigated to identify opportunities for improved marketing, distribution, and customer engagement.
Conclusion
The analysis provides management with a clearer understanding of sales performance, customer behavior, product profitability, and market contribution. The interactive Power BI dashboard can support ongoing performance monitoring and more informed business decisions.



<img width="1672" height="941" alt="Global E-Commerce Sales Dashboard" src="https://github.com/user-attachments/assets/d84dedf4-d993-447f-b999-3902c0d23a23" />
<img width="1672" height="941" alt="Global E-Commerce Executive Dashboard (1)" src="https://github.com/user-attachments/assets/98853c9e-3f8f-4806-a4fe-075049b43042" />
