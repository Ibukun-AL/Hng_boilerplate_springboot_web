# Spring Boot Boilerplate

## Overview

This Spring Boot boilerplate provides a solid foundation for building a modern web application. It includes basic project structure, essential dependencies, and example setups for various functionalities such as authentication, user management, blog, charts, and more. The project is configured with PostgreSQL.

## Project Structure
src
├── main
│ ├── java
│ │ └── com
│ │ └── example
│ │ └── Hng_boilerplate_springboot_web
│ │ ├── Configs
│ │ │ └── SecurityConfig.java
│ │ ├── Controllers
│ │ │ ├── AuthController.java
│ │ │
│ │ ├── DTOs
│ │ │ └── UserDto.java
│ │ ├── Models
│ │ │ └── User.java
│ │ │
│ │ ├── Repositories
│ │ │ └── UserRepository.java
│ │ ├── Services
│ │ │ ├── UserService.java
│ │ │
│ │ └── Hng_boilerplate_springboot_web.java
│ └── resources
│ ├── application.properties

## Getting Started

### Prerequisites

- Java 17
- PostgreSQL
- Maven

### Installation

1. **Clone the repository:**

```bash
git clone https://github.com/Ibukun-AL/Hng_boilerplate_springboot_web.git
cd Hng_boilerplate_springboot_web

2. **Configure the database:**
Configure the database:
Update the application.properties file with your PostgreSQL configuration.

3. **Run the application:**
mvn spring-boot:run
