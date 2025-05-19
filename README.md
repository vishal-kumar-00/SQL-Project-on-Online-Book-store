# SQL-Project-on-Online-Book-store

 Project Summary: 
 
 Online Bookstore Database
This project involves designing and querying a relational database for an Online Bookstore using PostgreSQL. It covers the full lifecycle from database creation to advanced data analysis using SQL.

🔧 Key Components

Database Name: OnlineBookstore

Tables:

Books – stores book details (title, author, genre, price, stock, etc.)

Customers – stores customer information (name, email, city, country, etc.)

Orders – records customer orders (order date, quantity, total amount, etc.)

Data Import: CSV files are used to populate each table with initial data.

📊 Query Features
Basic Queries:

Retrieve books by genre or publication year

Filter customers by country

Get orders within specific dates or above a certain value

Track total stock and find the most/least expensive or available books

Advanced Queries:

Aggregate book sales by genre and author

Identify high-spending customers and popular books

Calculate total revenue

Track inventory remaining after orders

Analyze customer behavior (e.g., repeat buyers)

✅ Key Learnings & Highlights
Use of foreign key relationships to connect tables

Application of aggregations, joins, and grouping

Filtering with date ranges, text matching, and numeric comparisons

Importance of data normalization and query optimization (e.g., indexing, using ILIKE, avoiding insert into SERIAL IDs)

