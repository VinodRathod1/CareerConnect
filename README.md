# 💼CareerConnect - Java Spring Boot with REST APIs, ReactJS, MongoDB

## 📌 Project Overview
**CareerConnect** is a simple full-stack web application designed to help users browse job listings and create new job posts. It is built using **Java Spring Boot** for the backend, **ReactJS** for the frontend, and **MongoDB** for data persistence.

This project demonstrates how to create a modular and scalable application using a modern technology stack, implementing essential CRUD operations with pagination and keyword-based searching.

---

## 🚀 Features

- 🔍 **Job Feed Page**: View all available job posts fetched from a local MongoDB database.
- 🔎 **Search Functionality**: Filter job posts based on keywords like `Java`, `Python`, etc.
- 📄 **Pagination**: Display 6 jobs per page with clickable page numbers for easy navigation.
- 📝 **Create Job Post**: Submit new job listings through a form and store them in MongoDB.

---

## 🛠️ Tech Stack

### Backend
- [Java Spring Boot](https://start.spring.io/)
- Spring Web (REST APIs)
- Spring Data MongoDB
- Swagger-UI
- Maven

### Frontend
- [ReactJS](https://reactjs.org/)
- Axios for HTTP requests
- React Router for navigation
- TailwindCSS for styling

### Database
- [MongoDB](https://www.mongodb.com/) (running locally)

---

## 📸 Project Screenshots

### 🏠 Home Page
The Landing Page of the Job Portal Platform.
![Home Page](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/01.png)

### 📝 Job Creating Form Page
`POST` - Create a new job
![Job Creating Form Page](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/02.png)

### 💼 Job Listings
`GET` - All job posts Listing here.
![Job Listings](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/03.png)

### 🔍 Search Job Post by Keyword  
`GET` - Search job listings by entering a keyword related to title, description, or company.  
![Search Job](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/04.png)

### 🧪 Swagger UI  
A developer-friendly interface to test and explore all RESTful APIs.  
Access via: `/swagger-ui.html`
![Swagger UI](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/05.png)

### ❌ 404 - Not Found Page  
Displays a user-friendly message when an invalid URL is visited.  
![404 Page](https://github.com/Mahmud-Alam/spring-boot-job-portal-app/blob/main/screenshots/06.png)

---

## 🏗️ Project Structure
### 🔙 Backend (Spring Boot)

```
job-portal-backend/
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.VinodRathod1.CareerConnect
│   │   │       ├── controller
│   │   │       ├── interfaces
│   │   │       ├── model
│   │   │       └──CareerConnectAppApplication.java
│   │   └── resources
│   │       ├── application.properties
│   │       ├── static/
│   │       └── templates/
│   └── test
│       └── java
│           └── com.VinodRathod1.CareerConnect
├── .env
└── pom.xml

```

### 🌐 Frontend (ReactJS)

```
CareerConnect-frontend/
 ├── public/
 ├── src/
 │   ├── api/
 │   ├── components/
 │   ├── pages/
 │   ├── App.jsx
 │   └── main.jsx 
 ├── package.json

```

---
