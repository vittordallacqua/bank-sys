### Bank management system in Java + JDBC

A simple Java banking system project using Object-Oriented Programming 
principles and MySQL database integration via JDBC.

This systmem is able to create a new bank account, make deposits, perform 
withdrawals, check account balance, and list all accounts

First steps:

* Create a MySQL database named `bankdb`.
* Execute the sqlScript.sql file to create the `accounts` table
* Edit the `db.properties` file with your database credentials
* Make sure `mysql-connector-java` is in your classpath.

How to run:

  ```
  > git clone https://github.com/vittordallacqua/bank-sys.git
  > cd bank-sys
  > javac src/**/*.java
  > java -cp src Main
  ```
  
Using VS Code:

* Make sure you have the "Extension Pack for Java" by Microsoft 
installed. This includes Language Support for Java™, Debugger for 
Java, Maven for Java, Project Manager for Java, and Test Runner for 
Java.

This project is licensed under the MIT License.
