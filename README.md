# Pizza Sales Analysis Using SQL

This project focuses on analyzing pizza sales data using SQL queries to derive insights into the sales trends, revenue generation, and customer preferences. The analysis is divided into three levels: Basic, Intermediate, and Advanced.

## Table of Contents
- [Project Overview](#project-overview)
- [Basic Analysis](#basic-analysis)
- [Intermediate Analysis](#intermediate-analysis)
- [Advanced Analysis](#advanced-analysis)
- [Data Structure](#data-structure)
- [Usage Instructions](#usage-instructions)

## Project Overview

The goal of this project is to explore and analyze pizza sales data through a series of SQL queries. By performing this analysis, we can gain insights into the following areas:
- Total number of orders and revenue
- Customer preferences for pizza types and sizes
- Revenue distribution over time
- Most popular pizza types and categories

The analysis is broken down into three sections:
1. **Basic Analysis**: Fundamental metrics, including total orders and revenue.
2. **Intermediate Analysis**: More detailed insights, including hourly distribution of orders and pizza category-wise sales.
3. **Advanced Analysis**: In-depth exploration of revenue distribution and contributions from different pizza types.

## Basic Analysis

The basic analysis focuses on answering foundational business questions:

1. **Total Orders**: The number of pizza orders placed.
2. **Total Revenue**: The total revenue generated from pizza sales.
3. **Highest-Priced Pizza**: Identifying the most expensive pizza on the menu.
4. **Most Common Pizza Size**: Determining the most frequently ordered pizza size.
5. **Top 5 Most Ordered Pizzas**: Listing the top 5 pizza types based on the number of orders.

## Intermediate Analysis

The intermediate analysis dives deeper into the dataset:

1. **Total Quantity of Each Pizza Category Ordered**: Join necessary tables to get the total quantity of pizzas ordered in each category (e.g., vegetarian, non-vegetarian).
2. **Order Distribution by Hour of the Day**: Analyzing the distribution of orders across different times of the day.
3. **Category-Wise Pizza Distribution**: Understanding how different categories of pizzas are ordered.
4. **Average Number of Pizzas Ordered Per Day**: Grouping orders by date to determine the daily average pizza order volume.
5. **Top 3 Pizza Types by Revenue**: Analyzing which pizza types generate the most revenue.

## Advanced Analysis

The advanced analysis focuses on more sophisticated insights:

1. **Percentage Contribution of Each Pizza Type to Revenue**: Determining how much each pizza type contributes to the total revenue.
2. **Cumulative Revenue Over Time**: Analyzing how revenue has accumulated over time, identifying growth patterns.
3. **Top 3 Pizza Types by Revenue for Each Category**: Identifying the top 3 most ordered pizza types by revenue for each pizza category (e.g., vegetarian, non-vegetarian).

## Data Structure

The data used in this analysis is structured across several tables, including but not limited to:
- **Orders Table**: Contains details about each order, such as order ID, pizza type, size, quantity, and total price.
- **Pizzas Table**: Contains information about different pizzas on the menu, such as pizza name, price, and category.
- **Customers Table**: Contains information about the customers who placed the orders, including customer ID and demographic data.
- **Order Details Table**: Contains line items for each order, including the specific pizzas ordered and their quantities.

## Usage Instructions

To use this project:
1. **Set up your SQL database**: Ensure that your database includes the relevant tables (Orders, Pizzas, Customers, etc.) with sample data.
2. **Run the SQL queries**: Execute the SQL queries corresponding to each analysis step to derive the insights.
3. **Review the results**: Analyze the output from each query to understand the pizza sales trends and customer preferences.

### Prerequisites
- SQL Database (MySQL, PostgreSQL, or any other SQL-based database)
- Sample pizza sales data in relevant tables

### Installation
To get started with the project, clone this repository and connect to your database:
```bash
git clone https://github.com/GaneshPrasadSahoo/pizza-sales-analysis-using-sql.git
