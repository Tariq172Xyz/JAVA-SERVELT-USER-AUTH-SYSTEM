Java Servlet User Authentication System

This project implements a secure and reliable authentication system for web applications using Java Servlets and JSP. It provides user registration, login, logout, and session management functionalities, ensuring that only authorized users can access protected pages.

The system follows the MVC architecture and demonstrates how session-based authentication works in a Java web application.

Features

User Registration – Allows new users to create accounts with unique credentials.

User Login – Authenticates users using email and password validation.

Session Management – Tracks active users using HTTP sessions and protects restricted pages.

Logout Functionality – Safely invalidates the session to prevent unauthorized access.

Route Protection – Prevents users from directly accessing protected pages without authentication.

Secure Redirection – Uses proper forwarding and redirection techniques after login and logout.

Technologies Used

Backend: Java Servlets
Frontend: JSP, HTML, CSS
Database: MySQL
Database Access: JDBC
Session Handling: HTTP Sessions
Server: Apache Tomcat

How It Works

User Registration
A new user signs up with name, email, and password. The credentials are stored in the database.

User Login
The system verifies the entered credentials against the database. If valid, a session is created for the user.

Session Management
The server maintains the user's session using HTTP sessions. Protected pages check for an active session before granting access.

Logout
The session is invalidated and the user is redirected back to the login page.
