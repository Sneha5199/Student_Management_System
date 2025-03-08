# Student_Management_System
# Spring Boot CRUD API with MySQL

Simple CRUD API using **Spring Boot**, **Spring Data JPA**, and **MySQL**.

## Technologies Used
- Spring Boot
- Spring Data JPA
- MySQL
- Postman

## API Endpoints

- **Get All Students:** `GET /students`
- **Get Student by ID:** `GET /students/{id}`
- **Create Student:** `POST /student/add`
- **Update Student:** `PUT /student/update/{id}`
- **Delete Student:** `DELETE /student/delete/{id}`

## Setup Instructions

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo-url.git
   cd your-project-folder
   ```

2. Configure `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/your_database
   spring.datasource.username=root
   spring.datasource.password=your_password
   spring.jpa.hibernate.ddl-auto=update
   ```

3. Run the application:
   ```sh
   mvn spring-boot:run
   ```

4. Test using Postman.

This project is a basic template for building RESTful APIs with Spring Boot.

