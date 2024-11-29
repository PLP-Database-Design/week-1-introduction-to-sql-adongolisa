# Assignment Answers

## 1. State and Explain the components of a DBMS (Database Management System)
A DBMS is a complex software system designed to manage databases. Here are its key components:

- **Database Engine**: The core service for storing, processing, and securing data. It controls access and manages the database’s storage, memory, and processing resources.
- **Database Schema**: Defines the structure of the database, including tables, views, indexes, and other database objects.
- **Query Processor**: Translates and executes database queries (such as SQL commands) from applications.
- **Storage Manager**: Handles data storage on physical media, including managing data structures, file organization, and storage allocation.
- **Transaction Manager**: Ensures that all database transactions are processed reliably and adhere to ACID properties (Atomicity, Consistency, Isolation, Durability).
- **Database Manager**: Administers the overall database, including defining data structures, user roles, and security measures.
- **Metadata**: Contains information about the structure of the database, data types, relationships, constraints, etc.

## 2. What is a relational database? Give 4 examples.
A relational database organizes data into tables (relations) where each table consists of rows and columns. Each row represents a record with a unique ID (primary key), and each column represents a data attribute.

**Examples**:
- **MySQL**
- **PostgreSQL**
- **SQLite**
- **Microsoft SQL Server**

## 3. State and Explain three classifications of SQL
SQL can be classified into several categories based on its functionality:

- **Data Definition Language (DDL)**: Commands that define the database structure. Examples include:
  - `CREATE` (to create tables or databases)
  - `ALTER` (to modify existing structures)
  - `DROP` (to delete tables or databases)

- **Data Manipulation Language (DML)**: Commands that manipulate data within the database. Examples include:
  - `SELECT` (to query and retrieve data)
  - `INSERT` (to add new data)
  - `UPDATE` (to modify existing data)
  - `DELETE` (to remove data)

- **Data Control Language (DCL)**: Commands that control access to the data. Examples include:
  - `GRANT` (to give access permissions)
  - `REVOKE` (to withdraw access permissions)

## 4. What is the difference between a Primary Key and a Foreign Key?
- **Primary Key**: A unique identifier for each record in a table. It ensures that no duplicate values exist and that no NULL values are allowed.
  - Example: In a `Students` table, the `student_id` might be the primary key.

- **Foreign Key**: A field in one table that uniquely identifies a row of another table. It creates a relationship between the two tables.
  - Example: In an `Enrollments` table, `student_id` could be a foreign key referencing the `Students` table’s `student_id`.

## 5. What is an Entity-Relationship Diagram?
An Entity-Relationship Diagram (ERD) is a visual representation of the entities within a database and the relationships between them. It helps in designing and understanding the database structure, showing how data is connected.

## 6. What are the advantages of relational databases?
- **Data Integrity**: Ensures accuracy and consistency of data through constraints and transactions.
- **Flexibility**: Easily adapts to changes in data requirements and structures.
- **Security**: Provides robust security mechanisms, including access controls and encryption.
- **Scalability**: Can handle increasing amounts of data and users efficiently.
- **Ease of Use**: SQL makes it relatively easy to interact with the database and perform complex queries.

## 7. State four types of data types used to store data in tables
- **Integer**: Stores whole numbers.
- **VARCHAR**: Stores variable-length character strings.
- **DATE**: Stores date values.
- **BOOLEAN**: Stores `TRUE` or `FALSE` values.

## 8. What is the purpose of a database management system (DBMS)?
The primary purpose of a DBMS is to provide a systematic way to create, retrieve, update, and manage data. It ensures data integrity, security, and accessibility while allowing multiple users and applications to interact with the database concurrently.
