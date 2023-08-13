# Java Database Project: Database Creation and Querying

This repository contains a Java project developed during the 2020/2021 academic year, focusing on creating and interacting with a database using Java programming. The project aimed to provide hands-on experience with database management, JDBC library utilization, and performing various database operations through Java.

## Project Objectives

The primary objectives of this project were as follows:

- **Database Initialization**: The project involved creating a database based on an Entity-Relationship (E-R) diagram. A Java program was developed to initialize the database and load initial data.

- **Database Interaction**: Java programs were developed to establish connections with the database using JDBC. These programs facilitated the execution of SQL queries, ranging from basic to complex, and retrieval of data from the database.

- **JDBC Mastery**: The project extensively utilized the Java DataBase Connectivity (JDBC) library to streamline database interactions. This library simplified handling unexpected situations while executing SQL queries and managing the database.

- **Transaction Management**: A crucial aspect of the project was implementing a transaction management system using Java. This ensured the integrity of data by treating multiple actions as a single unit.

## Key Learning Points

Throughout the project, the following skills were acquired:

- Establishing connections between Java code and a Database Management System (DBMS).
- Crafting and executing diverse SQL queries using appropriate JDBC classes.
- Managing SQL query results within Java code.
- Effective handling of exceptions arising from query execution.
- Proficiency in managing transactions through Java code.

## Project Execution

The project was executed using a virtual machine equipped with MySQL. MySQL Workbench facilitated tasks such as importing databases and running SQL scripts. The coding phase took place in Eclipse, a Java Integrated Development Environment (IDE), which was configured with the JDBC library, specifically "mysql-connector-java-5.1.38-bin.jar," located in the "C:\eclipse\CONECTOR_MYSQL" directory.

## Project Structure

The project revolved around a database encompassing details about series on streaming platforms, user reviews, and comments. Key tables included series, genres, seasons, episodes, and users. The Entity-Relationship diagram provided the blueprint for the tables and their relationships.

## Implemented Methods

The central class of the project, "SeriesDatabase.java," contains methods such as opening and closing connections, table creation, CSV data loading, specific data retrieval, and user photo management. The implementation aligned with project guidelines and specifications.
