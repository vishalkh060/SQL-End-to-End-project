Pizza Sales Analysis and Optimization
## Project Overview
This project is an end-to-end SQL analysis aimed at addressing common issues in pizza sales and identifying strategies for sales optimization. Using data on orders, pizza types, and order details, this project explores patterns in sales, customer preferences, and other key insights that can drive business improvements.

## Table of Contents
Project Objectives
Dataset
Project Structure
Key SQL Queries
Insights and Findings
Setup and Usage
Future Enhancements
Contributing
License
## Project Objectives
Analyze Sales Trends: Uncover patterns in daily, weekly, and seasonal sales.
Optimize Sales Performance: Identify high and low-performing products, peak sales times, and strategies to boost revenue.
Customer Behavior: Analyze popular pizza types, toppings, and combinations.
Inventory Planning: Provide insights for managing stock levels based on historical sales to reduce waste and costs.
## Dataset
This project uses a pizza sales dataset comprising four main CSV files:

order_details.csv: Contains details of individual items in each order, including:

order_id: Unique identifier for each order.
pizza_id: Identifier for the specific pizza type.
quantity: Number of units of a specific pizza in the order.
orders.csv: Lists each order’s metadata:

order_id: Unique identifier for each order.
date: Date of the order.
Additional fields may include order time, customer details, etc.
pizza_types.csv: Describes each pizza type and its ingredients:

pizza_type_id: Unique identifier for the pizza type.
name: Name of the pizza.
category: Pizza category (e.g., vegetarian, non-vegetarian).
ingredients: List of ingredients for each pizza type.
pizzas.csv: Information on pizzas by size and type:

pizza_id: Unique identifier for each pizza.
pizza_type_id: Identifier connecting each pizza to its type.
size: Size of the pizza (small, medium, large, etc.).
