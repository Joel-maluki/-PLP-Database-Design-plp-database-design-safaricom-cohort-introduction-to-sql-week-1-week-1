
## 1. State and Explain the components of a DBMS (Database Management System)

A DBMS consists of several components that work together to manage and manipulate databases efficiently:
- **DBMS Engine**: Core service responsible for data storage, retrieval, and updates.
- **Database Schema**: Defines the structure of the database (tables, views, relationships, etc.).
- **Query Processor**: Translates and optimizes SQL queries.
- **Database Management Software**: Tools for managing data and performing queries.
- **Data Dictionary**: Repository of metadata describing the database structure.
- **Transaction Management**: Ensures that database transactions are processed reliably (ACID properties).
- **Concurrency Control**: Ensures consistency during simultaneous data access.
- **Backup and Recovery**: Mechanisms for database recovery in case of failures.

## 2. What is a relational database? Give 4 examples.

A relational database is a type of database that stores data in tables (relations), with rows (records) and columns (attributes). It supports querying and manipulation of data using SQL.

**Examples of relational databases**:
1. MySQL
2. PostgreSQL
3. Oracle Database
4. Microsoft SQL Server

## 3. State and Explain three classifications of SQL

SQL is classified into three main categories:
- **DQL (Data Query Language)**: Used to query the database, e.g., `SELECT`.
- **DML (Data Manipulation Language)**: Used to manipulate data, e.g., `INSERT`, `UPDATE`, `DELETE`.
- **DDL (Data Definition Language)**: Used to define and manage database structure, e.g., `CREATE`, `ALTER`, `DROP`.

## 4. What is the difference between a Primary Key and a Foreign Key?

- **Primary Key**: A unique identifier for each record in a table. It cannot contain `NULL` values.
- **Foreign Key**: A key used to link one table to another, referencing the primary key of another table. It may contain `NULL` values.

## 5. What is an Entity-Relationship Diagram (ERD)?

An Entity-Relationship Diagram (ERD) is a visual representation of entities (tables) in a database and the relationships between them. It helps to design and understand the structure of a database.

## 6. What are the advantages of relational databases?

- **Data Integrity**: Enforces consistency through constraints (primary keys, foreign keys).
- **Flexibility**: Supports complex queries using SQL.
- **Data Security**: Provides access control mechanisms.
- **Scalability**: Can handle large volumes of data.
- **ACID Compliance**: Ensures transactions are processed reliably.

## 7. State four types of data types used to store data in tables

- **VARCHAR**: Stores variable-length text.
- **INT**: Stores integer values.
- **DATE**: Stores date values.
- **FLOAT**: Stores floating-point numbers.

## 8. What is the purpose of a database management system (DBMS)?

The primary purpose of a DBMS is to provide a systematic and efficient way to store, manage, and retrieve data from a database. It ensures data integrity, security, and consistency while supporting concurrent access and data manipulation.

---

### How to edit a markdown file

To edit a markdown file, use the following basic syntax:
- **Headings**: `#` for headings.
- **Bold**: `**text**`.
- **Italic**: `*text*`.
- **Lists**: `-` for unordered lists, numbers for ordered lists.
- **Links**: `[text](URL)`.
- **Images**: `![alt text](image URL)`.
