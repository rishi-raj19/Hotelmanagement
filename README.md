# Hotelmanagement

The Hotel Management System is a Spring Boot application that provides management functionalities for rooms.

1. Features
- Add a new room
- Retrieve a room by ID
- Retrieve all rooms
- Update a room
- Delete a room

2. Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- h2-db (or any other supported relational database)
- RESTful APIs

3. Getting Started

- Prerequisites
  Java Development Kit (JDK) 11 or higher
  h2-database or another supported relational database
  Your preferred IDE (e.g., IntelliJ, Eclipse)

4. Installation
- Clone the repository: git clone url
- Import the project into your IDE.
- Configure the database connection in the application.properties file:
spring.datasource.url=jdbc:mysql://localhost:3306/Hotel_db spring.datasource.username=db_username spring.datasource.password=db_password
- Run the application:
mvn spring-boot:run
- The application will start running on http://localhost:8080.

5. API Endpoints
- Hotel API
- POST /api/v1/Hotel-app/add-room: Add a new room.
- GET /api/v1/Hotel-app/find-room/id/{id}: Retrieve a room by ID.
- GET /api/v1/Hotel-app/find-all: Retrieve all Rooms.
- PUT /api/v1/Hotel-app/update-Room/id/{id}: Update a Room by ID.
- DELETE /api/v1/Hotel-app/delete-Room/id/{id}: Delete a Room by ID.
