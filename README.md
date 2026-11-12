# MyHostelManagement

A Java Swing and MySQL based Hostel Management System developed using Apache NetBeans.

## Features

- User login
- Room management
- New student registration
- Student record management
- Student fee management
- Current and left student records

## Technologies Used

- Java
- Java Swing
- Apache NetBeans IDE
- MySQL
- JDBC

## Requirements

- Java JDK
- Apache NetBeans IDE
- MySQL Server
- MySQL JDBC Connector


## Setup Instructions

### Requirements
- Java JDK
- Apache NetBeans IDE
- MySQL Server
- MySQL Workbench
- MySQL Connector/J

### Installation Steps

1. Download or clone this repository.
2. Open the project in Apache NetBeans.
3. Open MySQL Workbench and connect to your local MySQL Server.
4. Open the `hostel.sql` file from the project folder.
5. Execute the complete SQL script to create the `hostel` database, tables, and sample records.
6. Open `Project.ConnectionProvider.java` in NetBeans.
7. Update the MySQL username and password according to your local setup.
8. Make sure MySQL Connector/J is added to the project libraries.
9. Build and run the project from NetBeans.

### Database Configuration

Update the database connection details in `ConnectionProvider.java`:

- Database: `hostel`
- Username: Your MySQL username
- Password: Your MySQL password

**Note:** Do not upload your actual database password to GitHub.

