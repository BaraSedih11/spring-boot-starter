![Spring_Boot_Starter_API](https://github.com/user-attachments/assets/dbd8c607-3427-4447-8378-21d23fc39ccc)

<div align="center">
  
  [![Java](https://img.shields.io/badge/Java-11-orange)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
  [![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.0-brightgreen)](https://spring.io/projects/spring-boot)
  [![Maven](https://img.shields.io/badge/Maven-3.8.5-blue)](https://maven.apache.org/)
</div>
This project is a **Spring Boot Starter** template that provides a foundation for building APIs. The project demonstrates an example of a RESTful API for managing a `Person` entity. It includes features such as basic CRUD operations and serves as a starting point for more complex Spring Boot applications.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Features
- Create, Read, Update, and Delete (CRUD) operations for `Person` entities.
- RESTful API following best practices.
- Built with Spring Boot, making it scalable and easy to extend.
- Simple structure for rapid development and deployment.

## Technologies Used
- **Java 11**: The programming language used for the project.
- **Spring Boot 2.7.0**: Simplifies the creation of production-grade Spring applications.
- **Maven 3.8.5**: Build and dependency management tool.
- **H2 Database** (Optional): In-memory database for development and testing.

## Getting Started

### Prerequisites
- Java 11 or higher.
- Maven installed on your system.
- (Optional) H2 database for in-memory testing.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/BaraSedih11/spring-boot-starter.git
   cd spring-boot-starter
   ```
2. Install the dependencies:
  ```bash
  mvn clean install
  ```

### Running the Application
To run the Spring Boot application, use the following command:

```bash
mvn spring-boot:run
```

* The application will start on `http://localhost:8080`. *

## API Documentation
The API exposes the following endpoints for managing Person entities:

* GET /api/v1/person: Retrieve all persons.
* GET /api/v1/person/{id}: Retrieve a specific person by ID.
* POST /api/v1/person: Create a new person.
* PUT /api/v1/person: Update an existing person.
* DELETE /api/v1/person/{id}: Delete a person by ID.

### Example JSON Payload for Creating a Person
```json
{
  "name": "Bara Al-Sedih"
}
```
