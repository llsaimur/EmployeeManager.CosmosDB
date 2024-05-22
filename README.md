# EmployeeManager.CosmosDB

Functionalities:
-Signing In to Employee Manager
-Creating a New User Account
-Listing All the Employees
-Inserting a New Employee
-Updating Existing Employee
-Deleting Existing Employee
-Signing Out of Employee Manager

***
I moved the Northwind database to the cloud using Azure SQL Database. The Employee Manager application then uses this database to perform the CRUD operations.
***

Features:
-The employee data now resides in a Cosmos DB database named Northwind2.
-Perform CRUD operations on Cosmos DB using the Microsoft Azure
Cosmos DB client library
-The application uses a custom cookie authentication without ASP. NET Core Identity. The user details such as user name, password, and role are also stored in the Cosmos DB database
