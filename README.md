# 📚 Exam Management System

A full-stack Exam Management System built using **React** for the frontend, **Spring Boot** for the backend, and **MySQL** for database operations. This system facilitates exam-related operations for **Students**, **Faculty**, and **Admins**, including features like exam result viewing, revaluation requests, and issue reporting.

---

## 🔍 Features

### 👨‍🎓 Student Role
- Login using registered credentials
- View internal and external exam details
- View internal and external exam results
- Submit **revaluation requests**
- Report issues related to exams
- Check the status of the requests

### 👨‍🏫 Faculty Role
- Login and access role-based dashboard
- Upload exam details
- Upload and manage internal exam results

### 🧑‍💼 Admin Role
- View and process revaluation requests
- Upload exam details
- Upload external exams result
- View reported issues from students
- Update the status of student requests

------------------------------------------------

## 🛠️ Tech Stack

| Layer       | Technology                     |
|-------------|--------------------------------|
| Frontend    | React.js, HTML, CSS            |
| Backend     | Spring Boot (Java)             |
| Database    | MySQL                          |
| API Comm    | REST APIs (Axios in frontend)  |
| Build Tool  | Maven                          |
------------------------------------------------


## ⚙️ Setup Instructions

### Backend (Spring Boot)

1. Open backend folder in your IDE.
2. Configure database credentials in `application.properties`.
3. Run the Spring Boot application.

Commands:
1) cd .\exam-backend\   
2) ./mvnw spring-boot:run

### Frontend (React)
1) Navigate to the frontend directory.
    cd .\exam-frontend\ 

2) Install dependencies and run the app:
    npm install
    npm run dev
