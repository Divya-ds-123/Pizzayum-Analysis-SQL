## Pizzahut analysis by MySQL
This project focuses on analyzing Pizzayum sales data to uncover insights into customer behavior, sales trends, and churn patterns. By leveraging SQL for data extraction, transformation, and analysis, key metrics such as customer retention rates, top-selling products, and sales performance.The insights are visualized to support strategic decision-making aimed at improving customer engagement and boosting sales. 

## Here's the Sql query with questions -
## use pizzahut;

-- Retrieve the total number of order placed ?

select count(order_id) as total_orders from orders

