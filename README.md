# Music_Store_Analysis_Project
A comprehensive SQL data analysis project exploring a digital music store's database to uncover business insights, customer behaviors, and revenue trends.
# 🎵 Music Store Data Analysis

## 📝 Project Overview
This project is a comprehensive data analysis of a digital music store using **SQL**. The goal of this project is to analyze the store's database and extract valuable business insights. By writing complex SQL queries, this project answers key questions about customer behavior, employee performance, sales trends, and the most popular music genres.

## 🗂️ Dataset Information
The dataset consists of multiple interrelated `.csv` files representing different aspects of the music store's operations:
* **Core Entities:** `employee.csv`, `customer.csv`
* **Inventory:** `artist.csv`, `album.csv`, `track.csv`, `genre.csv`, `media_type.csv`
* **Sales Data:** `invoice.csv`, `invoice_line.csv`
* **Collections:** `playlist.csv`, `playlist_track.csv`

## 📊 Database Schema
The relationships between the tables are mapped out in the provided Entity-Relationship Diagram (ERD). 

![Music Store Schema](schema_diagram.png)

## 🛠️ Tools & Technologies Used
* **Language:** SQL
* **Techniques Used:** Joins, Aggregate Functions, Common Table Expressions (CTEs), Subqueries, Window Functions, and Data Filtering.

## 💡 Key Business Questions Answered
The `Music_Store_Query.sql` file contains the queries used to answer business questions such as:
1. Which countries have the most invoices?
2. Which city has the best customers (highest revenue)?
3. Who is the best customer (the one who has spent the most money)?
4. What is the most popular music genre in a specific country?
5. Which artists have earned the most revenue?

*(Note: Feel free to update this list with the exact questions you solved in your SQL file!)*

## 🚀 How to Run the Project
1. Download all the `.csv` files provided in this repository.
2. Import the `.csv` files into your preferred SQL database management system (e.g., PostgreSQL, MySQL, MS SQL Server, or SQLite).
3. Ensure the tables are created following the relationships outlined in `schema_diagram.png`.
4. Open and execute the queries in `Music_Store_Query.sql` to view the analysis and insights.

## 📬 Contact
Created by [Rahul](https://github.com/rahulstats-analyst) - feel free to reach out for collaborations or questions!
