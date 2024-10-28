# Role-Based Authentication System
## Description
This project is a full-stack application that implements role-based authentication. It allows users to log in and access different parts of the system based on their assigned roles (e.g., admin, user). Built with a Spring Boot backend and a ReactJS frontend, this system uses MySQL to store user and role data securely.
## Features
-  User Registration & Login: Allows new users to register and existing users to log in.
-  Role-Based Access: Restricts access to certain features based on user roles.
-  JWT Authentication: Secures the backend API with JSON Web Tokens.
-  API Endpoints: Provides various endpoints to manage users, roles, and permissions.
-  Responsive Frontend: User-friendly interface built with React.
## Installation
## Prerequisites
- Java(JDK 17 Or hieghr).
- React.js  library.
- MySQL.
- Maven.
## Backend Setup (Spring Boot)
Step 1: Clone the Repository and Navigate to Backend Directory
Start by cloning the repository to your local machine and navigate to the backend folder.
```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name/foldername
```
This will navigate you to the backend folder.

Step 2: Configure the MySQL Database.
1. Create a New Database.
- Login to mySQL server.
  ```
  mysql -u root -p
  ```
- Create new database.
  ```
  sql
  create database database_name;
  ```
- Note down the database name, username, and password you use, as you’ll need them for the next step.
2. Update Database Configuration in application.properties:
  ```
  # Database Configuration
spring.datasource.url=jdbc:mysql://localhost:3306/role_based_auth_system
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```
3. Add JWT Secret Key.
- Add a secret key for JWT (JSON Web Token) authentication to the application.properties file:
```
properties
jwt.secret=your_jwt_secret_key
```






  






