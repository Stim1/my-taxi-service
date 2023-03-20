# 🚕 **TAXI SERVICE** 🚕

### **A simple web-application that supports authentication , registration and other CRUD methods.**

### **Technologies used in application :** 

- Java 11;
- MySQL;
- Apache Tomcat 9.0.73;
- Apache Maven;
- jsp;
- jstl;
- html;
- Java Servlet;
- Java Database Connectivity (JDBC);

####  **Features :**

- registration like a driver.
- authentication like a driver.
- create/update/remove a car.
- create/update/remove a driver.
- display list of all manufactures.
- display list of all cars.
- display list of all drivers.
- display list of cars of current driver.
- delete method in which you can delete cars, drivers, and manufacturers.
- logout system;

### **How to start project locally :** 

- To get the actual parameters of the database tables, run script from the resources/init_db.sql file in the  MySQL Workbench.
- In the util/ConnectionUtil replace the variables URL, USERNAME, PASSWORD, JDBC_DRIVER with your own information.
- install and configure Tomcat 9.0.73(use war exploded deployment). If you decide to install version 10 and above, you should use a different dependency for servlets and JSTL as well.
- use mvn clean package to build the project, and to check if everything correct.
- Run the project, application will automatically open in browser.