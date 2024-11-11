# Understanding RDD 

The notebook performs the following analysis on customer, order, and order item data:

## 1. Find Top 10 Customers by Total Spend

1. Joins order and order item data to calculate total spend per customer
2.  Sorts the results to find the top 10 highest spending customers


## 2. Find Top 10 Products by Total Quantity Sold

1. Analyzes the order item data to calculate the total quantity sold for each product
2. Sorts the results to find the top 10 best-selling products


## 3. Count Customers from Caguas City

1. Filters the customer data to find all customers from the city of Caguas
2. Reports the total number of customers from Caguas


## 4. Count customers that have spent more than $1000 in total

1. Joins order and order item data 
2. Count after filtering out customers who have spend more than $1000
