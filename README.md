# Motorcycle-Wholesale-Revenue-Analysis-Using-SQL
📊 Business Problem:
The company wanted to analyze wholesale revenue across different product lines, warehouses, and months while accounting for payment processing fees.

🔍 What I Did:
• Filtered wholesale transactions from sales data
• Calculated net revenue after payment fees
• Grouped results by product line, warehouse, and month
• Used SQL aggregation functions and date extraction techniques
• Generated business-ready insights for decision-making

🛠️ Skills Applied:
✅ SQL
✅ Data Cleaning
✅ Aggregations (SUM, GROUP BY)
✅ Filtering (WHERE)
✅ Date Functions
✅ Business Analytics


the following table called sales:

Sales
Column	Data type	Description
order_number	VARCHAR	Unique order number.
date	DATE	Date of the order, from June to August 2021.
warehouse	VARCHAR	The warehouse that the order was made from— North, Central, or West.
client_type	VARCHAR	Whether the order was Retail or Wholesale.
product_line	VARCHAR	Type of product ordered.
quantity	INT	Number of products ordered.
unit_price	FLOAT	Price per product (dollars).
total	FLOAT	Total price of the order (dollars).
payment	VARCHAR	Payment method—Credit card, Transfer, or Cash.
payment_fee	FLOAT	Percentage of total charged as a result of the payment method.
Your query output should be presented in the following format:

product_line	month	warehouse	net_revenue
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_one	---	---	---
product_two	---	---	---
...	...	...	...
