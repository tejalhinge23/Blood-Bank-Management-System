



# 🩸 Blood Bank Management System (SQL):

This project is a SQL-based Blood Bank Management System designed to manage and track information about blood donors, receivers, and blood types. It uses relational database concepts with constraints, relationships, and queries to ensure data integrity and efficient retrieval.


# 📌 Project Overview:

The system stores details about:

Blood types and their IDs

Donors with demographic and donation details

Receivers with required blood type and contact details

It also includes SQL queries to retrieve insights such as donor/receiver counts, matching blood types, and filtering based on conditions.


# 🛠 Database Schema:

bloodtype – Stores unique blood types and IDs

donar – Stores donor personal details, contact info, blood group, and donation dates

receiver – Stores receiver details, required blood group, and linked donor information.


# 🔗 Relationships:

receiver.b_id → Foreign key referencing bloodtype.blood_id (Cascade on delete/update)


# 📂 SQL Operations:

The project includes:

Database creation (CREATE DATABASE, USE)

Table creation with constraints (PRIMARY KEY, FOREIGN KEY, NOT NULL)

Data insertion (INSERT INTO)

Data retrieval (SELECT, JOIN, GROUP BY, ORDER BY, WHERE)

Subqueries for advanced filtering.


# 📈 Sample Queries:

Count of receivers by state

Count of donors by blood group

Male donors older than 30

Donors from a specific state in a given year

Donors with the same blood type as a specific receiver

Join queries for matching donors and receivers in the same state

Aggregations for donor/receiver counts by blood type

Subqueries for age comparisons and matching blood groups


# 💡 Key Features:

Efficient relational database structure

Strong data integrity using constraints

Realistic sample dataset for testing

Query set covering both basic and advanced SQL concepts.
