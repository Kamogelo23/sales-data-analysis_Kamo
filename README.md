
#Sales Data Analysis
Project Description:
This project involves analyzing a sales dataset to gain insights into sales trends, customer behavior, and business performance. The analyses include data cleaning, exploratory data analysis, data visualization, and customer segmentation.

Dataset:
The dataset includes sales data from an unnamed company, with details about orders placed, customers, product categories, and profits. It contains the following fields:

order_id: ID for the order
order_date: Date the order was placed
ship_date: Date the order was shipped
ship_mode: Mode of shipping
customer_id: ID for the customer
customer_name: Name of the customer
segment: Market segment of the customer
country_region: Region of the country where the order was placed
city: City where the order was placed
state: State where the order was placed
postal_code: Postal code of the delivery location
region: Region of the delivery location
product_id: ID for the product
category: Category of the product
sub_category: Sub-category of the product
product_name: Name of the product
sales: Sales revenue from the order
quantity: Quantity of the product ordered
discount: Discount applied to the order
profit: Profit made from the order
Installation:
The analysis was performed using Python and requires the following libraries:

pandas
matplotlib
seaborn
Analyses Performed:
Exploratory Data Analysis: We performed an initial exploration of the data to understand the distribution of variables and the relationships between them.

Data Visualization: We created visualizations to better understand the trends and patterns in the data. This included:

Sales over time
Sales by category
Profit by region
Sales vs. Profit
Customer Segmentation: We segmented customers based on their purchase history, using Recency, Frequency, and Monetary (RFM) value.

Results:
Sales demonstrated a clear seasonality, with certain months having significantly higher sales.
The "Technology" category had the highest sales, followed by "Office Supplies" and "Furniture".
The "West" and "East" regions were the most profitable.
There was not a strong correlation between sales and profit, suggesting that higher sales do not necessarily translate to higher profit.
Based on the RFM analysis, customers were divided into three segments: high value, mid value, and low value.

