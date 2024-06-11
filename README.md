# SuperPOS-System
SuperPOS is a Java-based Point of Sale (POS) system designed to manage sales, inventory, and customer transactions efficiently. This application is developed using the NetBeans IDE and integrates with a MySQL database to store and retrieve data.

## Features
Category Management: Add, update, and delete product categories.
Product Management: Manage products including adding, updating, and deleting items.
Sales Transactions: Process sales and print receipts.
Inventory Management: Track product stock levels.

## Technologies Used
Java: Core application logic.
Swing: User interface components.
MySQL: Database for persistent storage.
JDBC: Database connectivity.
NetBeans IDE: Development environment.

# Installation and Setup

### 1.Clone the repository
 git clone https://github.com/yourusername/superpos.git

### 2.Import the project into NetBeans

 Open NetBeans IDE.
 Go to File > Open Project and select the cloned repository.

### 3.Set up the MySQL database

 Create a MySQL database named superpos.
 Import the provided SQL script to set up the tables (superpos.sql).

### 4.Configure database connection

 Ensure your database credentials (username and password) match those in the code
 con1 = DriverManager.getConnection("jdbc:mysql://localhost/superpos", "root", "1234");

### 5.Run the application:

 In NetBeans, right-click the project and select Run.
