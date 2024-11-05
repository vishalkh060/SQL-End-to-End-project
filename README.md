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

Project Structure
The repository is organized as follows:

data/: Contains the raw data files (order_details.csv, orders.csv, pizza_types.csv, pizzas.csv).
queries/: SQL query files used to explore and analyze the data.
scripts/: SQL scripts for creating tables, importing data, and generating reports.
README.md: Documentation of the project (this file).
## Key SQL Queries
The project includes a set of SQL queries designed to answer business-related questions, such as:

Sales by Product: Identifies which pizzas contribute most to total sales.
Peak Sales Analysis: Finds the busiest days and times for orders.
Customer Preferences: Determines the most popular pizza types, combinations, and ingredients.
Inventory Insights: Helps with inventory planning by analyzing trends in pizza ingredient use.
Each query file includes comments explaining the purpose of the query, as well as sample outputs.

## Insights and Findings
Key insights from the analysis include:

Top-Selling Products: Insights into the most popular pizzas and sizes.
Optimal Sales Times: Peak sales occur during specific times and days, allowing for improved staffing and inventory planning.
Customer Preferences: Data on the most popular ingredients and pizza combinations.
Inventory Optimization: Recommendations for managing stock levels to reduce waste.
