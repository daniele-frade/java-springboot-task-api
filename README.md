# Simple Task API (Spring Boot + H2 + Frontend)

This is a basic learning project that demonstrates how to build a simple REST API using Java Spring Boot, Spring Data JPA, H2 in-memory database, and a minimal HTML/JavaScript frontend.

## What does it do?
- Provides a REST API to create and list tasks (with title and completed status)
- Stores tasks in an in-memory H2 database
- Includes a simple frontend to interact with the API visually

## Endpoints
- `GET /api/tasks` — List all tasks
- `POST /api/tasks` — Create a new task (JSON body: `{ "title": "...", "completed": false }`)

## How to run

### 1. Requirements
- Java 17+
- Maven

### 2. Start the backend
```
mvn spring-boot:run
```
The API will be available at `http://localhost:8081/api/tasks` and the H2 console at `http://localhost:8081/h2-console`.

### 3. Start the frontend
You can use the Live Server extension in VS Code or any static server to open `frontend/index.html` in your browser.

- The frontend will connect to the backend at `http://localhost:8081/api/tasks`.
- You can add and list tasks visually.

## Notes
- This project is for educational purposes only and is intentionally simple.
- No authentication, validation, or advanced features are included.
- CORS is enabled for all origins for easy local testing.

---
Feel free to use, modify, and experiment with this code to learn the basics of Spring Boot APIs and frontend-backend integration!
# java-springboot-task-api
A simple REST API for a To-Do list, built with Java &amp; Spring Boot.
