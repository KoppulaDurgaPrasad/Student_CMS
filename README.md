<table align="center">
  <tr>
    <td valign="middle">
      <img src="Frontend/public/icon.png" height="80"/>
    </td>
    <td valign="middle">
      <h1 style="margin: 0 0 0 12px;">
        Student CMS (Student Course Management System)
      </h1>
    </td>
  </tr>
</table>

<p align="center">
  A Full Stack Duo Project built collaboratively by two developers.
</p>

---

# 🤝 Contribution

This project was developed as a **Duo Full Stack Project**.

Both contributors:

- Worked on **Frontend Development (React, UI Design, API Integration)**
- Worked on **Backend Development (Spring Boot, REST APIs, JPA, Hibernate)**
- Designed system architecture together
- Tested APIs using Postman
- Deployed frontend, backend, and database successfully

---

## 🚀 Live Demo

- 🌐 **Frontend:** https://student-cms-omega.vercel.app/  
- ⚙️ **Backend:** https://student-cms-h0so.onrender.com 

---

# 🛠️ Tech Stack

## 🔹 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html" height="60"/>
  <img src="https://skillicons.dev/icons?i=css" height="60"/>
  <img src="https://skillicons.dev/icons?i=react" height="60"/>
</p>

- HTML  
- CSS  
- React  

---

## 🔹 Backend

<p>
  <img src="https://skillicons.dev/icons?i=java" height="60"/>
  <img src="https://skillicons.dev/icons?i=spring" height="60"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hibernate/hibernate-original.svg" height="60"/>
</p>

- Java  
- Spring Boot  
- Spring Data JPA  
- Hibernate  

---

## 🔹 Database

<p>
  <img src="https://skillicons.dev/icons?i=mysql" height="60"/>
</p>

- MySQL Compatible  
- Hosted on **TiDB Cloud**

---

## 🔹 API Testing

<p>
  <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" height="60"/>
</p>

- Postman

---

# 🏗️ System Architecture

<p align="center">
  <img src="Frontend/public/architecture.png" width="950"/>
</p>

### 🔄 Architecture Overview

The system follows a **3-Tier Architecture**:

### 🖥️ Client Tier (React SPA)
- React Single Page Application
- Deployed on Vercel
- Communicates with backend using HTTPS (REST APIs)
- Uses Axios for JSON request/response handling

### ⚙️ Application Tier (Spring Boot)
- REST Controllers (API Endpoints)
- Service Layer (Business Logic)
- Repository Layer (Data Access)
- DTOs for Data Transfer
- Hibernate (ORM Layer)
- Deployed on Render

### 🗄️ Data Tier
- Relational Database (TiDB Cloud)
- MySQL-Compatible Distributed SQL Database
- Executes SQL queries from backend

> This architecture ensures scalability, maintainability, and separation of concerns.

---

# ✨ Features

## 👩‍🏫 Faculty Module

### 📝 Assignment Management
- Create assignments through frontend
- Upload assignment questions
- Students download questions
- Students submit response answers
- Faculty can:
  - View total submission count
  - View submitted count
  - View not submitted count
  - Download student responses
  - Evaluate answers offline

### 🧪 Quiz Management
- Create quiz using Google Forms
- Upload quiz link through frontend
- Students attempt quiz using link
- Automatic marks & responses available in Google Sheets

### 📚 Course Management
- Add NPTEL course links
- Manage course details
- Students can view added NPTEL courses

 ### 📢 Notification Management
- Faculty can create notifications about:
  - Current events
  - Important announcements
  - Academic updates
- Students can view notifications immediately after login

## 👨‍🎓 Student Module

### 📝 Assignments
- Download assignment questions
- Submit answers

### 🧪 Quizzes
- Attempt quiz via Google Form
- View marks (if enabled by faculty)

### 📚 Courses
- View NPTEL courses added by faculty
- Access course materials

### 📢 Notifications
- View latest notifications upon login
- Stay updated with faculty announcements
---

# 🔐 Security

- Session-based authentication using `HttpSession`
- Role-based access control (Faculty / Student)
- CORS configuration

---

# ⚙️ Run Locally

## 1️⃣ Clone Repository

```bash
git clone https://github.com/KoppulaDurgaPrasad/Student_CMS.git
cd Student_CMS
```

---

## 2️⃣ Backend Setup (Spring Boot)

If backend is in root folder:

```bash
mvn clean
mvn install
mvn spring-boot:run
```

If backend is inside a `backend` folder:

```bash
cd backend
mvn clean
mvn install
mvn spring-boot:run
```

---

## 3️⃣ Frontend Setup (React)

```bash
cd frontend
npm install
npm start
```

--- 


## 🚀 Deployment

- 🌐 **Frontend deployed on Vercel**  
- ⚙️ **Backend deployed on Render**  
- 🗄️ **Database hosted on TiDB Cloud**

---

# 👨‍💻 Contributors

- **Durga Prasad Koppula**  
  https://github.com/KoppulaDurgaPrasad  

- **Chaitanya Keerthan**  
  https://github.com/chaitanyakeerthan
  
---

⭐ If you like this project, give it a star!
