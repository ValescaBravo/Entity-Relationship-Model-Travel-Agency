# Travel Agency Database Project

In this project, we explore the development of a database for a hypothetical travel agency, covering the entire process from entity-relationship (ER) modeling to implementation in MySQL using SQL.

## Project Overview

We began by creating an entity-relationship model in the Dia program, defining the structure of our business logic. The ER model was then transformed into a relational model using Vertabelo, an online database modeling tool. Afterward, we used SQL to create the tables and insert data into MySQL.

## Data Generation

To populate the database with data, we used a combination of online tools and Excel:

+ Mockaroo: This tool was used to generate sample data based on our specified attributes.
+ Excel: We applied some rules to generate random data, which was later exported to CSV for bulk import.
  
## Implementation Details

 Using SQL, we implemented the following key elements:

+ Tables: Created tables for clients, packages, and reservations based on our relational model.
+ Data Loading: Manually inserted a record into the clients table to demonstrate the process. We then used bulk imports from CSV files to populate the database with data.
+ Queries: Developed several SQL queries to demonstrate the retrieval and analysis of data within the database.
  
## Connecting to RStudio 

To explore alternative methods of querying and analyzing data, we connected the Travel Agency's MySQL-hosted database with RStudio. This allowed us to use R's powerful data visualization and analysis tools to query the database and gain further insights.

## Tools and Technologies

The following tools and technologies were used in this project:

+ MySQL: For database management and data storage.
+ Dia: For entity-relationship modeling.
+ Vertabelo: For converting the ER model to a relational model.
+ Mockaroo: For generating sample data.
+ Excel: For additional data generation and manipulation.
+ DBeaver: For SQL query management and data import/export.
+ RStudio: For exploring and analyzing the database with R's data science capabilities.
  
# Conclusion

Database Management Systems (DBMSs) are invaluable tools for any business, allowing for a high degree of automation in querying and data management. In our project, MySQL proved to be a robust and user-friendly solution for storing, retrieving, and manipulating data. Tools like DBeaver facilitated import/export processes and SQL syntax management. By connecting to RStudio, we also explored different methods of querying and analyzing the database.
