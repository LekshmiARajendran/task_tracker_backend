# Task Tracker Backend

This is a simple Task Tracker backend built using Kotlin, Spring Boot, and PostgreSQL. It handles user registration and authentication as part of a basic task management system.

## 🚀 Features
- User registration (`/api/auth/register`)
- User login (`/api/auth/login`)
- Spring Boot REST API structure
- Integrated with PostgreSQL database using Spring Data JPA

## 🛠 Tech Stack
Kotlin, Spring Boot, PostgreSQL, JPA, Gradle

## ⚙️ Installation & Run

1. Clone the repository:
   git clone https://github.com/LekshmiARajendran/task_tracker_backend.git

2. Open the project in IntelliJ IDEA.

3. Configure your PostgreSQL database credentials in `src/main/resources/application.yml`.

4. Run the project:
- Use the green run button on `TaskTrackerApplication.kt` or
- Execute via terminal: `./gradlew bootRun`

5. The backend will start at `http://localhost:8080`

## 📬 API Usage

You can test the endpoints using Postman:

### Register a User
POST http://localhost:8080/api/auth/register
Content-Type: application/json

{
"username": "testuser",
"password": "testpass"
}

shell
Copy
Edit

### Login
POST http://localhost:8080/api/auth/login
Content-Type: application/json

{
"username": "testuser",
"password": "testpass"
}

## 📁 Project Structure

src
└── main
└── kotlin
└── com.example.tasktracker
├── controller
│ └── AuthController.kt
├── model
│ └── User.kt
├── repository
│ └── UserRepository.kt
├── service
│ └── UserService.kt
└── TaskTrackerApplication.kt

---

✅ Built with Kotlin + Spring Boot + PostgreSQL – 2025
