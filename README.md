# Role Based Access Control (RBAC) with Spring Boot and JWT

## Solution Overview

![Solution Overview](https://github.com/IMS94/spring-boot-jwt-authorization/blob/master/authorization_process.png?raw=true "Solution Overview")

## Role Based Access Control
An example of role based access control.

![RBAC Example](https://github.com/IMS94/spring-boot-jwt-authorization/blob/master/rbac_sample.png?raw=true "Solution Overview")

## JWT Authentication Overview

![Solution Overview](https://github.com/IMS94/spring-boot-jwt-authorization/blob/master/solution_overview.png?raw=true "Solution Overview")

## Getting Started

- Use `mvn clean install` in the project root directory to build the project. 
- Run the main class, `com.example.springboot.jwt.JwtApplication` to start the application.

## Endpoints

- `/login` -> Public endpoint which returns a signed JWT for valid user credentials (username/password)
- `/products` -> Contains several endpoints to add and remove product entities. Protected by JWT authentication and
authorized based on role.
