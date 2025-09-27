# JDBC Connection Demo

This is a simple Java project demonstrating how to connect to a **PostgreSQL database** using **JDBC**.

## Features
- Connects to PostgreSQL using JDBC.
- Prints a success message when connected.
- Can be used as a template for CRUD operations.

## Prerequisites
- Java 8 or above
- PostgreSQL installed and running
- PostgreSQL JDBC driver in your classpath

## How to Run
1. Update database credentials in `jdb_connection.java`:

```java
String url = "jdbc:postgresql://localhost:5432/testdb";
String user = "postgres";
String password = "admin123";
