Expense Tracker API
This is a basic full-stack expense tracker application made using Spring Boot and Vanilla JavaScript. The project was built to understand how frontend and backend applications communicate using REST APIs and how data can be stored and retrieved from a database.

Users can add expenses through the frontend interface and view all saved expenses instantly without refreshing the page.

Tech Stack
Java 21
Spring Boot
Spring Web
Spring Data JPA (Hibernate)
H2 Database
HTML, CSS, JavaScript (Fetch API)
Features
Add new expenses and store them in the database
Fetch and display all saved expenses
REST API implementation using proper HTTP methods
Backend validation using annotations like @NotNull, @Positive, and @NotBlank
Dynamic frontend updates using JavaScript and Fetch API
CORS configuration for frontend-backend communication
Simple 3-layer architecture using Controller, Service, and Repository

How to Run the Project

Clone the repository:

git clone https://github.com/YourUsername/expense-tracker-api.git

Open the project folder and run the Spring Boot application:

./mvnw spring-boot:run

Open the application in your browser:

http://localhost:8080/index.html

To access the H2 database console:

http://localhost:8080/h2-console

This project helped me get hands-on experience with Spring Boot, REST APIs, database integration using JPA, and frontend-backend communication using JavaScript.
