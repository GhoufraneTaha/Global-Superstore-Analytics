# Global Superstore Analytics

This project focuses on analyzing sales data from a global retail store to uncover trends, insights, and patterns that support better business decision-making.  
The analysis covers yearly, category, product, customer, and regional performance using real-world sales data.

The project demonstrates a complete workflow: processing raw data, generating meaningful summaries using SQL, and creating interactive dashboards in Power BI for clear and effective visualization.


## Project Structure

Global-Superstore-Analytics/
|
├── data/
| ├── raw/
| | └── Global_Superstore_data.xlsx
| |
| └── processed/
|  ├── yearly_total_sales.csv
|  ├── yearly_total_profit.csv
|  ├── category_summary.csv
|  ├── subcategory_summary.csv
|  ├── top10_products.csv
|  ├── top10_customers.csv
|  ├── region_summary.csv
|  ├── top20_cities.csv
|  ├── market_summary.csv
|  └── category_avg_discount.csv
|
├── sql/
| ├── create_table.sql
| ├── queries.sql
| └── csv_conv_queries.sql
|
├── dashboard/
| └── Superstore_PowerBI_visualization.pbix
|
├── screenshot/
 └── Global_Superstore_dashboard.png


## Project Overview

The main objectives of this project are:

- **Data processing and analysis**  
  Cleaning and transforming the raw dataset using PostgreSQL, pgAdmin, and psql to generate structured summaries for sales, profit, categories, subcategories, top products, and regions.

- **Data visualization**  
  Building interactive dashboards in Power BI to present key metrics and insights in a clear and accessible format.

- **Business insights**  
  Identifying trends and patterns across regions, categories, and customers to support data-driven decision-making.


## Key Insights

This project provides insights into:

- Yearly trends in sales and profit  
- Performance of product categories and subcategories  
- Top-performing products and customers  
- Regional distribution of sales and profit  
- Average discount per category and its impact on profitability  

These insights help businesses better understand sales performance, optimize strategies, and identify opportunities for improvement.


## Tools and Technologies

- **PostgreSQL** – database creation, querying, and data analysis  
- **pgAdmin** – database management  
- **psql** – executing SQL scripts and exporting processed data  
- **Power BI** – interactive dashboards and data visualization  
- **Excel / CSV** – raw and processed data storage  


## Dashboard Preview

The Power BI dashboard includes:

- Area charts  
- Funnel charts  
- Line charts  
- Clustered column charts  

These visuals highlight:

- Regional sales performance  
- Category and subcategory contributions  
- Top products and customers  
- Yearly sales and profit trends  

A preview of the dashboard is available in:
-screenshot/Global_Superstore_dashboard.png
