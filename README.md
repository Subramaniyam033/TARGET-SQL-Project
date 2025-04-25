# TARGET-SQL-Project
Problem Statement:
	Target seeks to improve its operations and customer experience in Brazil by analysing historical order data FROM 2016 to 2018. The objective is to uncover insights related to order fulfilment, pricing, payments, shipping, customer behaviour, product performance, and reviews. These insights will help Target enhance operational efficiency, optimize pricing and delivery strategies, and improve customer satisfaction to strengthen its position in the Brazilian retail market.

•	Get the time range between which the orders were placed.
Code:
SELECT
min(order_purchase_timestamp) as first_order,
max(order_purchase_timestamp) as last_order
FROM
`scalerproject-454408.target_sql_project.orders`
;

