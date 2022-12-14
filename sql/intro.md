---
sidebar_position: 1
title: Introduction
---

# Introduction to Databases and SQL

**In this tutorial, we'll learn about databases, different types of databases and their uses.**

A database is an organized collection of data so that it can be easily accessed. To manage these databases, **Database Management Systems (DBMS)** are used.

---

## Types of DBMS

In general, there are two common types of databases:

<ul>
  <li>Non-Relational</li>
  <li>Relational</li>
</ul>

---

## Non-Relational Database Management System (Non-RDBMS)

In Non-RDBMS, data is stored in key-value pairs. For example:

<p align="center">
  <img src="https://www.programiz.com/sites/tutorial2program/files/nosql.png" width="60%"/>
</p>

Here, customers' data are stored in key-value pairs.

**Commonly used Non-RDBMS**: MongoDB, Amazon DynamoDB, Redis, etc.

---

## Relational Database Management System (RDBMS)

In RDBMS, data is stored in **tabular format**. For example,

| customer_id | first_name | last_name | phone        | country |
| ----------- | ---------- | --------- | ------------ | ------- |
| 1           | John       | Doe       | 817-646-8833 | USA     |
| 2           | Robert     | Luna      | 412-862-0502 | USA     |
| 3           | David      | Villa     | 208-917-3291 | France  |

Here, `customers` is a table inside the database.

---

## Introduction to SQL

**Structured Query Language (SQL)** is a standard query language that is used to work with relational databases.

We use SQL to

<ul>
  <li>create databases</li>
  <li>create tables in a database</li>
  <li>read data from a table</li>
  <li>insert data in a table</li>
  <li>create databases</li>
  <li>update data in a table</li>
  <li>delete data from a table</li>
</ul>

---

## SQL Example: Read Data From a Table

Let's take a look at an example:

```sql
SELECT first_name, last_name FROM Customers;
```

Here, this SQL command selects the first name and last name of all customers from the customers table.

<center>
  <img src="https://www.programiz.com/sites/tutorial2program/files/sql-example.png" width="60%"/>
</center>

---

SQL is used in all relational databases such as MySQL, Oracle, MSSQL, PostgreSQL etc.
:::tip

**Node:** The major SQL commands are similar in all relational databases. However, in some cases, SQL commands may differ.

:::
