Name:ASHA JYOTHI TALLAPUDI
Company:CODTECH IT SOLUTIONS
ID:CT3MTDS048
Domain:Python Programming
Duration:July to October
Mentor:Muzammil Ahmed

**Overview of the Project**
**Inventory Management System Project**
This project is a simple Inventory Management System built using Python with a Graphical User Interface (GUI) created using Tkinter. The system allows users to manage a product inventory for a store or warehouse. It includes user authentication, product management (adding/viewing products), and a structured SQLite database to store data securely.

**Features:**
User Authentication:

Users must log in with a username and password to access the system.
Passwords are stored securely in the database using SHA-256 hashing.

Add Products:

Users can add products to the inventory by providing:
Product name
Description
Price
Quantity
The product information is stored in the SQLite database.
View Products:

Users can view all products currently stored in the inventory.
Products are displayed with their ID, name, description, price, and quantity.
Database Integration:

SQLite is used as the backend database to store user data, product details, and potential future sales data.

**Key Components:**
User Registration

Users are registered manually in the code initially (for admin purposes).
Passwords are hashed using hashlib to ensure security.
Login System:

Users log in with their credentials.
The system checks for valid usernames and hashed passwords from the database before granting access.
Product Management:

Products can be added to the inventory via a form in the GUI.
Each product has a name, description, price, and quantity.
Product data is stored in the products table of the database.
Viewing Products:

A simple GUI window lists all the products currently stored in the database.
Product details (ID, name, description, price, quantity) are displayed in a table format.
Technologies Used:
Python: The primary programming language for the application.
Tkinter: Used for building the GUI components (login window, product forms, product view).
SQLite: A lightweight relational database for storing user and product data.
Hashlib: Used for securely hashing passwords before saving them in the database.

**Conclusion:**
The Inventory Management System is a practical project for managing the stock of a store or warehouse. It introduces the fundamentals of user authentication, product management, and database handling using SQLite. The GUI makes it easy to use, even for users without programming knowledge, and can be expanded to include more advanced features such as reports, notifications, or multi-user support.
![Screenshot (30)](https://github.com/user-attachments/assets/4dfd4d6d-3f51-4180-8b07-c08789ae24f2)






