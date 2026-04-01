# Rest API Project (Spring Boot)

## 📌 Overview

This project is a RESTful API built using **Spring Boot**. It demonstrates a layered architecture with controllers, services, repositories, and models for handling backend operations efficiently.

---

## 🏗️ Project Structure

```
src/main/java/com/AML2A/Rest_Api
│
├── controller     # Handles HTTP requests (API endpoints)
├── service        # Business logic layer
├── repository     # Database interaction layer
├── model          # Entity classes (data models)
└── RestApiApplication.java  # Main Spring Boot entry point
```

---

## 🚀 Technologies Used

* Java 17
* Spring Boot
* Spring Web
* Spring Data JPA
* Maven
* Eclipse IDE

---

## ⚙️ How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/your-username/Rest-Api.git
```

### 2. Navigate to the project

```
cd Rest-Api
```

### 3. Run the application

Using Maven:

```
mvn spring-boot:run
```

OR run `RestApiApplication.java` directly from your IDE.

---

## 🌐 API Endpoints (Example)

| Method | Endpoint           | Description         |
| ------ | ------------------ | ------------------- |
| GET    | /api/students      | Fetch all students  |
| GET    | /api/students/{id} | Fetch student by ID |
| POST   | /api/students      | Add new student     |
| PUT    | /api/students/{id} | Update student      |
| DELETE | /api/students/{id} | Delete student      |

---

## 🧪 Testing the API

You can test the API using:

* Postman
* cURL
* Browser (for GET requests)

Example:

```
http://localhost:8080/api/students
```

---

## 📂 Build

To build the project:

```
mvn clean install
```

---

## ⚠️ Notes

* Ensure port **8080** is free before running.
* Configure database settings in `application.properties` if using a database.
---

## 📄 License

This project is for educational purposes.
