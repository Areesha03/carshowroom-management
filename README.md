# carshowroom-management
                            **Car Showroom Management System - Project Overview**
**1. Project Introduction**
This project is a desktop-based Car Showroom Management System built using Java (Swing for GUI) and
MySQL as the backend database. It allows users to manage car inventory, customer data, and sales records
in an integrated and user-friendly manner.
**2. Modules of Java Application**
- Dashboard: Central navigation window for accessing other modules.
- Car Inventory: Allows adding, deleting, and viewing car data (Car ID, Brand, Model, Price, etc).
- Customers: Add/view customer records.
- Sales: Record new sales, view existing ones, and calculate total and average prices.
- Settings: Application preferences.
**3. Database Design (MySQL)**
The database named 'car_showroom_db' consists of 4 main tables:
1. cars (car_id, brand, model, price, etc)
2. customers (customer_id, name, phone, email)
3. sales (sale_id, car_id, customer_id, sale_date, price)
4. users (user_id, username, password) - if login feature is enabled.
Each table is connected with proper primary and foreign key relationships.
**4. Java-MySQL Connectivity**
Java connects to MySQL using JDBC (Java Database Connectivity).
Classes use 'DBConnection.getConnection()' method to create connection objects.
All database operations (insert, delete, read) are done through PreparedStatements.
**5. Key Features**
- Dropdown filters and search functionality for easy data lookup.
- Automatic ID generation and summary updates (total sales, average price).
- Proper exception handling and validation.
- GUI designed using Java Swing with modern layout and responsiveness.
**6. How to Run**
1. Open the project in an IDE (NetBeans or IntelliJ).
2. Make sure MySQL server is running and car_showroom_db is imported.
3. Update JDBC credentials in DBConnection.java if needed.
4. Run DashboardFrame.java to start the app.
**7. Conclusion**
This project demonstrates complete integration of frontend GUI with backend database using Java and
MySQL. It solves a real-world problem for car showroom owners, reducing manual data management and
improving efficiency
