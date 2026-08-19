**🏨 Hotel Management System**

A Java-based Hotel Management System designed to simplify and manage essential hotel operations through a user-friendly desktop application.

The system provides modules for guest management, room management, employee management, check-in/check-out, room search, and administrative operations, with MySQL used for database management.

**✨ Features**

 •👤 Guest Management – Add and manage customer details
 •🛏️ Room Management – Add, update, and manage hotel rooms
 •🔎 Room Search – Search for available rooms
 •🧑‍💼 Employee Management – Manage employee records
 •🏢 Department Management – Manage hotel departments
 •🧾 Check-In / Check-Out – Manage guest stays
 •🚗 Pickup Management – Manage guest pickup information
 •👨‍💼 Manager Information – Maintain manager records
 •🔐 Login & Authentication – Secure application access
 •📊 Dashboard – Centralized access to hotel operations
 •💾 Database Integration – Store and retrieve data using MySQL
 •🔄 CRUD Operations – Create, read, update, and manage records


**🛠️ Tech Stack**

        Technology	                            Purpose
       ☕ Java	                           Application development
       🖥️ Java Swing / AWT                	Desktop GUI
       🔗 JDBC	                            Database connectivity
       🗄️ MySQL	                            Data storage
       💡 IntelliJ IDEA	                    Development environment
       🔌 MySQL Connector/J	MySQL-          Java connection

**📂 Project Structure**

Hotel-Management-System/
│
├── src/
│   └── Hotel/
│       └── Management/
│           └── System/
│               ├── addDriver.java
│               ├── AddEmployee.java
│               ├── AddRoom.java
│               ├── admin.java
│               ├── CheckOut.java
│               ├── con.java
│               ├── CustomerInfo.java
│               ├── Dashboard.java
│               ├── Department.java
│               ├── Employee.java
│               ├── Login.java
│               ├── Login2.java
│               ├── ManagerInfo.java
│               ├── NewCustomer.java
│               ├── PickUp.java
│               ├── Reception.java
│               ├── Room.java
│               ├── SearchRoom.java
│               ├── Splash.java
│               ├── UpdateCheck.java
│               └── UpdateRoom.java
│
├── README.md
└── .gitignore


**🧩Main Modules**

**👤 Customer Management**

Allows hotel staff to register new guests and manage customer information.

**🛏️ Room Management**

Provides functionality to add rooms, update room details, and manage room availability.

**🔎 Room Search**

Helps staff search and identify available rooms based on hotel records.

**🧑‍💼 Employee Management**

Maintains employee information and supports employee-related operations.

**🏢 Department Management**

Manages different departments and their associated information.

**🧾 Check-In & Check-Out**

Handles guest check-in and check-out processes and maintains stay-related information.

**🚗 Pickup Management**

Manages guest pickup and driver-related information.

**🔐 Login & Admin**

Provides login functionality and administrative access to the system.

**📊 Dashboard & Reception**

Provides a centralized interface from which major hotel management operations can be accessed.


**⚙️ Requirements**

Before running the project, make sure you have:

JDK 8 or above
MySQL Server
IntelliJ IDEA or another Java IDE
MySQL Connector/J
🗄️ Database Setup
Install and start MySQL Server.
Create a database for the application.
Create/import the required tables.
Open con.java.
Update the database connection details.

**Example**:

String url = "jdbc:mysql://localhost:3306/hotelmanagement";
String username = "root";
String password = "your_password";

Replace the values with your own MySQL configuration.

Note: Do not upload your real database password to GitHub. Use your local credentials or environment variables.


**▶️ How to Run**

1. Clone the Repository
git clone https://github.com/your-username/guest-management-system.git
2. Open the Project

Open the cloned project in IntelliJ IDEA.

3. Configure MySQL

Create the required database and configure the connection in con.java.

4. Add MySQL Connector

Add MySQL Connector/J to the project classpath.

5. Run the Application

Run:

Splash.java

or the appropriate entry-point class configured in the project.


**🔄 Application Flow**

Login
  ↓
Dashboard / Reception
  ↓
 ┌───────────────┬───────────────┬───────────────┐
 ↓               ↓               ↓
Customer       Rooms          Employees
 ↓               ↓               ↓
Check-In     Search Room     Departments
 ↓
Check-Out

**🎯 Project Objectives**

The main objectives of this project are to:

Automate basic hotel management operations.
Reduce manual record keeping.
Maintain guest and room information digitally.
Improve accessibility of hotel records.
Practice Java desktop application development.
Implement database connectivity using JDBC and MySQL.
Understand real-world CRUD-based application development.


**📚 Learning Outcomes**

Through this project, the following concepts were practiced:

Object-Oriented Programming
Java GUI Development
Java Swing and AWT
JDBC Connectivity
MySQL Database Management
CRUD Operations
Exception Handling
Database Queries
Modular Application Development
Desktop Application Design


**🚀 Future Enhancements**

The project can be further enhanced with:

🌐 Web-based version
📱 Mobile application
💳 Online payment integration
📧 Email notifications
📱 SMS notifications
📊 Advanced reports and analytics
🔐 Role-based access control
☁️ Cloud database integration
🏨 Online room booking
🧾 Automated invoice generation

**👨‍💻 Author**

Mukund Kumar Mishra

B.Tech – Artificial Intelligence & Machine Learning

Interested in Software Development, Java, SQL, and Application Development.

**⭐ Support**

If you find this project useful, consider giving the repository a ⭐ on GitHub.

**📄 License**

This project is created for educational, learning, and portfolio purposes.
