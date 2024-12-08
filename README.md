# Spring Boot Starter Template

A secure Spring Boot starter template with basic security configuration.

## Features

- Spring Boot 3.4.0
- Java 21
- Spring Security integration
- Docker Compose support
- Spring Dev Tools for development
- Complete test setup with security testing support

## Prerequisites

- Java 21 or higher
- Maven 3.9+ (or use included Maven wrapper)
- Docker (optional, for Docker Compose support)

## Quick Start

### Instructions to Set Up the Application in a Local Environment

1. **Install Java 21 or Higher**

   - Ensure that Java Development Kit (JDK) version 21 or higher is installed.
   - Verify the installation by running:
     ```sh
     java -version
     ```

2. **Install Maven 3.9+ or Use Maven Wrapper**

   - Install Apache Maven version 3.9 or higher.
   - Alternatively, use the provided Maven wrapper scripts:
     - `mvnw` for Unix/Linux/MacOS
     - `mvnw.cmd` for Windows

3. **Clone the Repository**

   - Clone the repository to the local machine:
     ```sh
     git clone <repository-url>
     ```
     Replace `<repository-url>` with the URL of the repository.

4. **Navigate to the Project Directory**

   - Change to the project directory:
     ```sh
     cd spring-boot-starter-template
     ```

5. **Build the Application**

   - Build the project using Maven:
     ```sh
     mvn clean install
     ```
     Or, if using the Maven wrapper:
     ```sh
     ./mvnw clean install
     ```

6. **Run the Application**

   - Start the application using Maven:
     ```sh
     mvn spring-boot:run
     ```
     Or, if using the Maven wrapper:
     ```sh
     ./mvnw spring-boot:run
     ```

7. **Access the Application**

   - Open a web browser and navigate to:
     ```
     http://localhost:${YOUR_APP_PORT:8080}
     ```