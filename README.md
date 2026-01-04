📊 SQL Data Analysis Project
📌 Project Overview

This project focuses on using SQL to extract, analyze, and interpret data from a relational database.
It is designed for Data Analytics / Data Analyst fresher-level portfolio projects and demonstrates practical SQL skills applied to real-world business questions.

🛠️ Tools & Technologies

Database: MySQL

Language: SQL

Tool: MySQL Workbench

Dataset: Sample Business / DVD Rental Dataset

📂 Project Structure
SQL-Data-Analysis-Project/
│
├── queries/
│   ├── basic_queries.sql
│   ├── joins.sql
│   ├── aggregations.sql
│   └── subqueries.sql
│
├── dataset/
│   └── database_schema.sql
│
└── README.md

🎯 Project Objectives

Practice basic to advanced SQL concepts

Perform data analysis to answer business-related questions

Build a strong SQL portfolio project for job applications

🧠 SQL Concepts Covered

SELECT, WHERE

ORDER BY, GROUP BY

HAVING clause

JOINs (INNER, LEFT, RIGHT)

Aggregate Functions (COUNT, SUM, AVG)

Subqueries

Aliases

📊 Business Questions Solved

How many inventory items are available in each store?

Who are the top customers based on total rentals?

Which film categories generate the most rentals?

How many total rentals occurred each year?

🧪 Sample SQL Query
SELECT 
    c.customer_id,
    CONCAT(c.first_name, ' ', c.last_name) AS customer_name,
    COUNT(r.rental_id) AS total_rentals
FROM customer c
JOIN rental r
ON c.customer_id = r.customer_id
GROUP BY c.customer_id
ORDER BY total_rentals DESC;

📈 Key Insights

Identified high-value customers based on rental frequency

Analyzed inventory distribution across stores

Evaluated customer behavior and rental trends over time

🚀 How to Run the Project

Open MySQL Workbench

Import the database schema from the dataset folder

Execute SQL files from the queries folder

Review and analyze the query results

👤 Author

Name: Alvi
Role: Aspiring Data Analyst
Skills: SQL, Excel, Power BI, Python

⭐ Note

This project is created for learning and portfolio purposes.
