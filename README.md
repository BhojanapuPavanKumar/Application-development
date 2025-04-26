Banking System — Java Minor Project
📖 Introduction
This project was developed during summer training to gain practical experience in Java application development. Using Java and Oracle 21c, a Banking System was created to manage employee and customer accounts effectively.

The application demonstrates real-world development processes, from requirement analysis to coding, database integration, and deployment.

🛠️ Project Workflow
Problem Understanding: Defined requirements and functionalities.

Design: Planned the architecture with classes and object interactions.

Setup: Installed JDK, Eclipse IDE, and necessary libraries.

Development: Built the core structure, following object-oriented principles like encapsulation and inheritance.

Testing: Conducted unit and integration tests to ensure reliability.

Deployment: Packaged the application into executable formats.

🔗 Database Integration
The application connects to an Oracle 21c database using JDBC.
Steps included:

Installing Oracle 21c and setting up schemas.

Using ojdbc.jar for database connectivity.

Establishing connection via DriverManager.getConnection() in Java.

Example:

java
Copy
Edit
Class.forName("oracle.jdbc.driver.OracleDriver");
Connection con = DriverManager.getConnection(
  "jdbc:oracle:thin:@localhost:1521:ORCLCDB",
  "username",
  "password"
);
📋 System Features
Employee Functions
Login

View Details

Add Customer Accounts

Manage Payments

Delete Accounts

Sign Out / Exit

Customer Functions
Login

View Details

Send Money

Check Balance

Sign Out / Exit

🗂️ Database Tables
EBACCOUNT (Employee Details): E_NO, E_NAME, E_MAIL, E_ADDRESS, E_DESIGNATION, E_MOBILENO, E_PASS

CBACCOUNT (Customer Details): C_NO, C_NAME, C_MAIL, C_ADDRESS, C_GENDER, C_MOBILENO, C_PASS

🖼️ Screenshots
(Screenshots of the GUI and database operations are included.)

📢 Conclusion
The Banking System project enhanced skills in Java programming, database management, and application deployment, providing strong practical exposure in software development.

