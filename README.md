# SQL-AdventureWorks-DB
### This SQL script operates on the AdventureWorks database and performs several queries related to sales data for the year 2020

Here's a breakdown of what each part does:

1. Total Revenue in 2020:
   - It calculates the total revenue generated in the year 2020 by summing up the TotalDue column from the SalesOrderHeader table for orders placed in 2020.

2. Top 5 Best-Selling Products in 2020:
   - It retrieves the top 5 best-selling products in 2020 based on the quantity sold. It joins the Product, SalesOrderDetail, and SalesOrderHeader tables to get the necessary information and filters the results for orders placed in 2020.

3. Monthly Revenue in 2020:
   - It calculates the revenue for each month in 2020.
   - It extracts the month from the OrderDate, groups the data by month, and calculates the total revenue for each month.

4. Top 5 Customers by Total Purchase Amount in 2020:
   - It retrieves the top 5 customers based on their total purchase amount in 2020.
   -It joins the Customer, Person, and SalesOrderHeader tables to get customer details and filters the results for orders placed in 2020. The results are then grouped by customer and sorted by the total purchase amount in descending order.

These queries provide valuable insights into the sales performance for the year 2020, including total revenue, top-selling products, monthly revenue trends, and top customers.
