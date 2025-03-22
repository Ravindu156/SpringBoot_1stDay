# Spring Boot Application

This is a simple Spring Boot application that provides basic REST API endpoints.

## Getting Started

### Prerequisites
- Java 17 or later
- Maven
- An IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. Build the project:
   ```sh
   mvn clean install
   ```
3. Run the application:
   ```sh
   mvn spring-boot:run
   ```

## API Endpoints

| Method | Endpoint   | Description                 |
|--------|-----------|-----------------------------|
| GET    | `/app/msg`  | Returns "Hello SpringBoot" |
| GET    | `/app/name` | Returns "My name is Spring Boot" |

## Deployment
This application can be deployed on any Java-supported environment. You can package the application as a JAR file and run it using:
   ```sh
   java -jar target/your-app.jar
   ```



