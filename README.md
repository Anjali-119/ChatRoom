# ChatRoom

This project is a simple chat room application built using Spring Boot. The application allows users to join chat rooms and send messages in real-time.

Table of Contents
Introduction
Features
Technologies Used
Getting Started
Prerequisites
Installation
Running the Application
Project Structure
Contributing
License
Introduction
The Chat Room Application is designed to demonstrate how to create a simple chat room using Spring Boot. Users can create chat rooms, join existing ones, and exchange messages in real-time.

Features
User registration and login
Creating and joining chat rooms
Sending and receiving messages in real-time
WebSocket-based communication
Technologies Used
Java 17
Spring Boot 3.x
Spring WebSocket
Spring Security
Spring Data JPA
H2 Database (for development and testing)
Thymeleaf (for server-side rendering)
Maven (for build and dependency management)
Getting Started
Prerequisites
Ensure you have the following installed on your local machine:

Java Development Kit (JDK) 17 or higher
Maven 3.6 or higher
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Anjali-119/ChatRoom.git
cd ChatRoom
Build the project using Maven:

bash
Copy code
mvn clean install
Running the Application
Start the application:

bash
Copy code
mvn spring-boot:run
Open your web browser and navigate to http://localhost:8282.

Project Structure
Here's a brief overview of the project's structure:

arduino
Copy code
chat-room-app
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── chatroom
│   │   │               ├── config
│   │   │               ├── controller
│   │   │               ├── model
│   │   │               ├── repository
│   │   │               ├── service
│   │   │               └── ChatRoomApplication.java
│   │   └── resources
│   │       ├── static
│   │       ├── templates
│   │       ├── application.properties
│   │       └── data.sql
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── chatroom
│                       └── ChatRoomApplicationTests.java
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
config: Contains configuration classes for WebSocket and security.
controller: Contains the web controllers.
model: Contains the entity classes.
repository: Contains the Spring Data JPA repositories.
service: Contains the service layer classes.
resources/templates: Contains the Thymeleaf templates.
application.properties: Configuration file for the application.
data.sql: Initial data for the H2 database.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

Fork the repository
Create a new feature branch (git checkout -b feature/new-feature)
Commit your changes (git commit -m 'Add new feature')
Push to the branch (git push origin feature/new-feature)
Open a pull request
