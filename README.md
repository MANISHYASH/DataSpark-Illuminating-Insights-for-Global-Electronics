DataSpark: Illuminating Insights for Global Electronics
========================================================

Project Overview
----------------
DataSpark: Illuminating Insights for Global Electronics is a retail analytics project that looks at the electronics industry. It aims to give useful insights into the sales data of a global electronics retailer. The project has an impact on different areas, including how products perform, who the customers are how stores do, and how currency exchange rates affect sales.

Objective
---------
The main goal of this project is to use data analytics methods to get insights that can help make smart business choices. The specific aims are:

- To find the best-selling products and groups.
- To study customer details and how they act.
- To check how stores do in different areas.
- To see how changes in currency rates affect sales.
- To create dashboards you can interact with to show the insights .

Data Description
----------------
The project utilizes multiple datasets related to products, sales, customers, stores, and exchange rates. The key datasets are:

1. Products Dataset:
   - Columns: brand, category, categorykey, color, productkey, subcategory, subcategorykey, unit cost usd, unit price usd

2. Sales Dataset:
   - Columns: currency code, customerkey, delivery date, line item, order date, order number, productkey, quantity, storekey

3. Customers Dataset:
   - Columns: birthday, city, continent, country, customerkey, gender, name, state, state code, zip code

4. Stores Dataset:
   - Columns: country, open date, square meters, state, storekey

5. Exchange Rates Dataset:
   - Columns: currency, date, exchange

Tools and Technologies
----------------------
The following tools and technologies were used in the project:

- Data Cleaning and Preprocessing: Python (Pandas, NumPy)
- Data Management: MySQL (XAMPP)
- Data Visualization: Power BI
- Project Management: Jupyter Notebooks

Data Preprocessing
------------------
Steps Involved:

1. Data Cleaning:
   - Handling missing values, particularly in the Delivery Date column by dropping rows with missing values.
   - Removing duplicates and irrelevant columns.

2. Data Transformation:
   - Merging datasets using common keys (e.g., productkey, customerkey, storekey).
   - Standardizing data formats across datasets (e.g., date formats).

3. Data Loading:
   - Importing cleaned and merged datasets into MySQL using XAMPP.
   - Loading data into Power BI for analysis and visualization.

Exploratory Data Analysis (EDA)
-------------------------------
We looked at the data to see how it was spread out how things were connected, and what patterns we could find. Here's what we did:

- Product Analysis: We checked sales data to figure out which products and categories were selling the most.
- Customer Demographics: We looked at customer info to understand how customers were split up by age, gender, and where they lived.
- Store Performance: We compared sales numbers to see how well stores were doing in different areas.
- Exchange Rate Impact: We studied how changes in exchange rates affected sales in different currencies.


Data Modeling and Analysis
--------------------------
Using SQL queries within Power BI, various insights were derived:

1. Top-Selling Products: Identified products with the highest sales volume and revenue.
2. Average Order Value: Calculated the average order value across different stores.
3. Sales by Region: Analyzed sales performance across different continents and countries.
4. Customer Segmentation: Segmented customers based on demographics and purchasing behavior.

Visualizations and Dashboard
----------------------------
An interactive dashboard was created in Power BI to visualize the insights derived from the data analysis. The key features of the dashboard include:

- Sales Overview: A comprehensive view of total sales, top-selling products, and sales by region.
- Customer Insights: Visual representations of customer demographics and purchasing patterns.
- Store Performance: A comparison of store performance metrics across different regions.
- Currency Analysis: Visualization of the impact of exchange rates on sales.

Conclusion
----------
The DataSpark project successfully provided valuable insights into the sales data of a global electronics retailer. The analysis helped in identifying key trends, customer segments, and high-performing products, enabling data-driven decision-making.




