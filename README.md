About the Project

This is my Event Management System project developed using Java and Spring Boot. The project is designed to provide a web interface for event-related activities, 
including event pages, user registration, forms, and booking-related pages.I used HTML, CSS, and Thymeleaf for the frontend and Java with Spring Boot for the backend. 
I followed the MVC architecture and separated the application into controllers, entities, repositories, service interfaces, and service implementations to keep the code organized.
I also worked on form validation for email, password, and phone number fields.

Technologies Used

Java 17 – Backend development
Spring Boot – Application development
Spring MVC – Handling web requests and controllers
HTML – Creating web pages
CSS – Styling the frontend
Database - Mysql
Thymeleaf – Rendering dynamic web pages
Spring Data JPA / Repositories – Data access, if configured in the project
Maven – Dependency management and project build


Features

User registration and login-related pages
Event-related pages and event information
Booking-related pages
Form handling using Spring MVC controllers
Email, password, and phone number validation
Dynamic HTML pages using Thymeleaf
Separate service and repository layers
Event images and other static resources


Project Structure

The project follows a layered structure based on MVC.
Controller: Handles requests from the user and manages application flow.
Entity: Contains classes representing application data, such as events, forms, and registration.
Repository: Handles data access operations.
Service Interface: Defines the application's service methods.
Service Implementation: Contains the implementation of service methods.
Templates: Contains the HTML and other view templates.
Static: Contains images, assets, and other static resources.

Folder Structure

EventManagement_SpringProject/
├── src/
│   ├── main/
│   │   ├── java/com/Happy/
│   │   │   ├── controller/
│   │   │   ├── entity/
│   │   │   ├── repository/
│   │   │   ├── serviceInterface/
│   │   │   ├── serviceImplementation/
│   │   │   └── EventManagementSpringProjectApplication.java
│   │   └── resources/
│   │       ├── static/
│   │       │   ├── assets/
│   │       │   └── gallery/
│   │       ├── templates/
│   │       └── application.properties
│   └── test/java/
├── pom.xml
└── README.md


How to Run the Project

Clone the repository:

git clone https://github.com/Preeti72-ankalagi/EventManagementProject.git

Open the project in Eclipse, Spring Tool Suite, or IntelliJ IDEA.

Make sure Java 17 and Maven are available.

Check application.properties and configure any required database settings.

Run EventManagementSpringProjectApplication.java as a Spring Boot application, or use:

mvn spring-boot:run

Open your browser and visit http://localhost:8080 if port 8080 is configured.


What I Learned
Through this project, I gained practical experience with Spring Boot and Spring MVC. I learned how to organize a Java application into different layers, 
connect controllers with service classes and repositories, create dynamic web pages using Thymeleaf, and validate user input.
