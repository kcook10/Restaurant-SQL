# Restaurant-SQL
 Created a data set and SQL queries to design a restaurant design model and program. This repository outlines the Data, Schema, and Queries.


    Brief Summary:

    A program that keeps track of orders at a restaurant. Customers are identified using a unique id and also store their first name, last name, and phone number. Each order has a unique order id, type, price, customer id, time, date, and table number. Each employee has a unique id, first name, last name, and title. Each store has a unique id, location, phone number, and supervisor id. The amount of orders a customer can make is unlimited, but each employee can be assigned to five orders maximum.

    Tentative Business Rules and Regulations:

    Each order belongs to a single customer; Each customer can have one or more orders Each order belongs to a single employee, each employee can have one to five orders Each store is overseen by one supervisor ;each supervisor can belong to only one store Orders are linked to their customers through the Customer Id Ensure data integrity by enforcing referential integrity constraints for foreign keys such as Customer Id and Super Id. Customer Ids, Order Ids, Employee Ids, and store Ids should be unique and used consistently.