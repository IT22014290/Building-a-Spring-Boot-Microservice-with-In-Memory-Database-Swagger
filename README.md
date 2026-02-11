# Building-a-Spring-Boot-Microservice-with-In-Memory-Database-Swagger
will be able to build a Spring Boot microservice with REST APIs, use an in-memory database, and document APIs using Swagger.

SLIIT | Department of Computer Science & Software Engineering |
Faculty of Computing
Module – Current Trends in Software Engineering (SE4010) | 2025 | Semester 1
DevOps Lab – 3
Building a Spring Boot Microservice with In-Memory Database & Swagger
Part 1 – Creating a Spring Boot Microservice
Objective: Create a simple RESTful microservice using Spring Boot.
Steps:
1 Go to Spring Initializr – https://start.spring.io
2 Project: Maven | Language: Java | Packaging: Jar
3 Group: com.sliit | Artifact: product-service
4 Add dependencies: Spring Web, Spring Data JPA, H2 Database, Springdoc OpenAPI UI
5 Generate and open the project in an IDE
Part 2 – Implementing REST APIs
Create a Product microservice with CRUD REST endpoints.
1 Create Product entity with id, name, and price
2 Create ProductRepository extending JpaRepository
3 Create ProductController
4 Implement POST, GET, GET by ID, and DELETE endpoints
Part 3 – Using an In-Memory Database (H2)
Use H2 database to persist data during runtime.
1 Configure H2 properties in application.properties
2 Enable H2 console
3 Run the application and access http://localhost:8080/h2-console
4 Verify table creation
Part 4 – Enabling Swagger (OpenAPI)
Expose API documentation using Swagger UI.
1 Add springdoc-openapi dependency
2 Start the application
3 Access Swagger UI at http://localhost:8080/swagger-ui.html 4 Test APIs using Swagger UI
Expected Outcome
Students will be able to build a Spring Boot microservice with REST APIs, use an in-memory database, and
document APIs using Swagger.
Submission
Upload your entire project to GitHub and submit the GitHub repository link in a .txt fil
