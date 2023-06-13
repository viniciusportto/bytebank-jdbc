# Java and JDBC: Working with a database
ByteBank is a project developed with the aim of learning JDBC (Java Database Connectivity) and it utilizes the MySQL database, along with the Hikari library for connection management.

## Features 🎉
The ByteBank project includes the following features:

- Connection to the MySQL database using JDBC.
- Efficient connection management with the help of Hikari.
- Basic Create, Read, Update, and Delete (CRUD) operations on the database.
- Transaction handling to ensure data integrity.

## Topics Covered in the JDBC Course 📖
The JDBC course covers the following topics:

1.Database Connection:

- Configuration and establishment of a connection to the database.
- Usage of connection strings to specify the location, port, database name, username, and password.

2.SQL Query Execution:

- Preparation and execution of SQL queries using the Statement and PreparedStatement interfaces.
- Retrieving query results, iterating over the results, and processing the returned rows.

3.Transaction Management:

- Understanding the concept of transactions and their importance in data integrity.
- Using transactions to group related operations and ensure atomicity of operations.

4.CRUD Operations (Create, Read, Update, Delete):

- Inserting data into tables using INSERT statements.
- Retrieving data using SELECT statements.
- Updating existing records using UPDATE statements.
- Deleting records using DELETE statements.

5.Metadata Manipulation:

- Accessing and manipulating information about the database, such as tables, columns, and data types.
- Using the DatabaseMetaData interface to obtain database information.

6.Error Handling:

- Dealing with exceptions and errors that can occur during database operations.
- Using try-catch blocks to catch and handle exceptions.

7.Best Practices and Performance:

- Utilizing resources like connection pools to improve performance and efficiency of database operations.
- Using PreparedStatements instead of Statements to avoid security issues and enhance performance.

8.Security Considerations:

- Preventing SQL injection attacks by using PreparedStatements and proper data sanitization.
- Implementing security best practices such as encryption of sensitive data and access restrictions to the database.

These are some of the key topics covered in the JDBC course, providing a solid foundation for interacting with databases using Java.

## Environment Setup ⚙️

Before running the project, make sure to set up the environment correctly. Follow the steps below:

1- Install MySQL Server on your machine if you haven't done so already.

2- Create a database in MySQL called "bytebank".

3- Import the "bytebank.sql" file located in the "sql" folder of the project to create the necessary tables.

4- Ensure that you have the MySQL JDBC driver on your classpath. You can add the driver manually or use a dependency management tool like Maven or Gradle.

5- Import the project into your favorite IDE.

## Running the Project ⚡

After setting up the environment and Hikari, you are ready to run the ByteBank project. Make sure your MySQL server is running and follow the steps below:

1.Execute the "Main" class to see the available operations.
2.Explore the available methods to create, read, update, and delete records in the database.
3.Observe how Hikari efficiently manages the connections to the database.

## Contributing 👥
If you would like to contribute to the development of the ByteBank project, feel free to send pull requests. Your contribution is much appreciated!
