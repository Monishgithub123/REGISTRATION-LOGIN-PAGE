# Spring Boot Registration Login Page

## Overview

This project is a simple registration and login system built using Spring Boot and MySQL. It allows users to register, log in, and access protected resources.

## Technologies Used

- **Spring Boot**: Framework for building Java-based enterprise applications.
- **MySQL**: Relational database for storing user information.
- **IntelliJ IDEA**: Integrated development environment used for coding and project management.

## Project Structure

spring-boot-registration-login
|-- src
| |-- main
| |-- java
| |-- net.javaguides.springboot
| |-- config
| |-- model
| |-- repository
| |-- service
| |-- SpringBootRegistrationLoginApplication.java
|-- src
| |-- main
| |-- resources
| |-- application.properties
|-- pom.xml


## Setup Instructions

1. Clone the repository:




2. Open the project in IntelliJ IDEA.

3.Configure MySQL database in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
spring.datasource.username=your_username
spring.datasource.password=your_password


4.Run the application using IntelliJ or with Maven:
5.Access the application at http://localhost:8080.


Usage:-
1.Register: Navigate to the registration page and fill in the required details.
2.Login: Once registered, log in with your credentials.
3.Access Protected Resources: Certain pages or features may be protected and accessible only to logged-in users.

Dependencies:-
1.Spring Boot Web
2.Spring Boot Data JPA
3.MySQL Connector
4.Thymeleaf (for the frontend)
5.Spring security





Contributing:-
Feel free to contribute to the project by forking and submitting a pull request. Bug reports and feature requests are welcome!
