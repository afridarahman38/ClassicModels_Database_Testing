# Database Testing with MySQL

## Overview
This project focuses on testing the database components of a software system to ensure data integrity, accuracy, and reliability. Database testing is crucial for identifying issues related to data storage, retrieval, and manipulation, helping maintain the overall quality of the software.

## Prerequisites
MySQL: Ensure that you have MySQL installed on your machine. You can download it from [MySQL's official website](https://www.mysql.com/downloads/)

## Key Objectives
- Data Accuracy: Verify that the data stored in the database accurately reflects the input and meets specified requirements.

- Data Integrity: Ensure that data integrity constraints, such as primary key and foreign key relationships, are maintained.

- Performance: Evaluate the performance of database queries and transactions under varying conditions to ensure optimal response times.

- Security: Verify that the database is secure against unauthorized access, SQL injection, and other potential security threats.

- Concurrency: Test the system's ability to handle multiple concurrent database transactions without data corruption or inconsistencies.

- Recovery: Assess the effectiveness of backup and recovery mechanisms to ensure data can be restored in case of failures.

## Project Structure
- SQL Scripts: Contains SQL scripts for creating and modifying the database schema.

- Test Data: Includes sample data used for testing different scenarios.

- Queries: Stores SQL queries used for testing and validating data retrieval.

- Test Cases: Detailed test cases covering various aspects of database functionality.

- Reports: Documentation and reports generated from database testing activities.

## How to Run Database Tests
- Database Setup: Ensure the database is properly configured with the required schema and test data.

- Test Execution: Execute the database test scripts, queries, and transactions using a testing framework or tools.

- Monitoring and Analysis: Monitor database performance, analyze query execution plans, and identify any anomalies or performance bottlenecks.

## Tables Used in this project
The MySQL sample database schema consists of the following tables:
- customers
- employees
- offices
- orderdetails
- orders
- payments
- productlines
- products

## Test Cases done in this project
- Checked table presence in the database schema
- Checked table name conventions
- Checked the number of columns in a table
- Checked the column name in a table
- Checked the data type of columns in the table
- Checked the size of the columns in a table
- Checked null fields in a table
- Checked column keys in a table

## Acknowledgments
Feel free to contribute, open issues, or provide feedback to make this project even better!
