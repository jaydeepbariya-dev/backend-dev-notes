## DBMS Fundamentals

Introduction to Databases

Database vs File System

DBMS vs RDBMS

Database Models

Relational, Hierarchical, Network, Object-oriented

Keys

Primary Key, Foreign Key, Candidate Key, Super Key, Composite Key

Relationships

One-to-One, One-to-Many, Many-to-Many

Normalization

1NF, 2NF, 3NF, BCNF

Transactions

ACID properties

Concurrency Control

Locks, Deadlocks, Isolation levels

Indexing & Views

B-Tree, Hash index

Views (Materialized vs Virtual)

Stored Procedures & Triggers (conceptual)

Backup & Recovery basics

--
## SQL

Purpose: Learn practical querying and data manipulation.

2.1 Basics

Creating Databases and Tables

Data Types

Constraints: PRIMARY, FOREIGN, UNIQUE, CHECK, NOT NULL

Basic CRUD

INSERT, SELECT, UPDATE, DELETE

2.2 Advanced Queries

Joins: INNER, LEFT, RIGHT, FULL, CROSS

Aggregate Functions: SUM, AVG, COUNT, MIN, MAX

GROUP BY and HAVING

ORDER BY, DISTINCT, LIMIT / OFFSET

Subqueries / Nested Queries

CASE statements

2.3 Functions & Operators

String functions (CONCAT, LENGTH, SUBSTR, TRIM)

Date/Time functions (NOW(), DATE_ADD(), DATE_DIFF())

Numeric functions (ROUND, CEIL, FLOOR)

Conversion functions (CAST, CONVERT)

2.4 Views, Indexes, and Constraints

Create and Drop Views

Materialized Views

Index creation and usage

Enforcing data integrity

2.5 Transactions & Concurrency

COMMIT, ROLLBACK, SAVEPOINT

Isolation Levels

Locks and Deadlocks (basic queries)

2.6 Performance & Optimization

EXPLAIN / EXPLAIN PLAN

Query optimization basics

Normalization vs Denormalization

--
## MongoDB (NoSQL)

Purpose: Learn document-based database concepts and querying.

3.1 Basics

MongoDB Overview

NoSQL vs SQL

Document, Collection, Database

Installation and Setup

MongoDB Shell and Compass

CRUD Operations

insertOne, insertMany

find, findOne

updateOne, updateMany

deleteOne, deleteMany

3.2 Advanced Queries

Filtering

Comparison operators ($eq, $ne, $gt, $gte, $lt, $lte)

Logical operators ($and, $or, $not)

Projection (selecting specific fields)

Sorting

Limit and Skip

Aggregation Framework

$match, $group, $project, $sort, $limit

Aggregate pipelines

3.3 Indexing & Performance

Creating Indexes

Single field, compound, text index

Explain plans for queries

Sharding & Replication basics

3.4 Data Modeling

Embedded documents vs References

Denormalization strategies

Handling relationships in MongoDB

3.5 Transactions (MongoDB 4.x+)

Multi-document ACID transactions

commitTransaction, abortTransaction

Session handling
