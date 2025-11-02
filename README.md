# 🧭 **JobHunter – Spring Boot + React Full Stack Application**

**JobHunter** is a modern full-stack web platform that simplifies the process of finding and applying for jobs. It’s built with a **React frontend** for an intuitive user experience and a **Spring Boot backend** that powers all business logic, data handling, and authentication features.

---

## 🚀 **Overview**

JobHunter serves as a fully functional job portal that enables:

* Candidates to browse and apply for jobs.
* Users to manage their profiles and resumes.
* Admins to oversee job listings and applications.

It’s designed to demonstrate real-world full-stack development with a clean architecture and practical features.

---

## ✨ **Core Features**

* 🔍 **Job Listings:** Explore available positions and filter them based on category or type.
* 👤 **User Profiles:** Create and update user information, resumes, and job preferences.
* 📨 **Job Applications:** Submit job applications directly through the portal.
* 🛠️ **Admin Dashboard:** Manage job posts, view applicants, and oversee platform activities.
* 🔐 **Authentication:** Secure login and signup system using JWT-based authentication.

---

## 🧩 **System Architecture (UML Overview)**

The diagram below outlines the system’s core structure, highlighting relationships between key components:

<img src="./showcase/chatuml-diagram.png" alt="UML Diagram" width="600px">

---

## 🖼️ **Screenshots**

| Home                                          | Login / Register                                                                                 |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| <img src="./showcase/home.png" width="400px"> | <img src="./showcase/login.png" width="400px"> <img src="./showcase/register.png" width="400px"> |

| Profile / Jobs                                                                                 | Admin Dashboard                                                                                               |
| ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| <img src="./showcase/profile.png" width="400px"> <img src="./showcase/jobs.png" width="400px"> | <img src="./showcase/adminApplications.png" width="400px"> <img src="./showcase/adminJobs.png" width="400px"> |

---

## 🧱 **Project Structure**

```
JobHunter/
├── frontend/   # React.js frontend
└── backend/    # Spring Boot backend API
```

---

## ⚙️ **Prerequisites**

Before setup, ensure that the following are installed:

* **Java 21+** (for Spring Boot backend)
* **Node.js 14+** (for React frontend)
* **MySQL** (for the database)

---

## 🧭 **Setup Guide**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ethicalByte1443/Job-Hunt.git
cd JobHunter
```

---

### 2️⃣ Setup the Frontend (React)

```bash
cd frontend
npm install
npm start
```

The app will start at → [http://localhost:3000](http://localhost:3000)

---

### 3️⃣ Setup the Backend (Spring Boot)

```bash
cd backend
mvn clean install
mvn spring-boot:run
```

Your API will be available at → [http://localhost:8080](http://localhost:8080)

---

### 🧾 Configure Environment

Update the `application.properties` file (`/backend/src/main/resources/application.properties`) with your credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/<database_name>
spring.datasource.username=<your_username>
spring.datasource.password=<your_password>

# Path to file uploads
upload.dir=C:/path/to/uploads/
```

---

## 📘 **API Documentation**

API endpoints are documented automatically with **Swagger**.
Access it via:

```
http://localhost:8080/swagger-ui/index.html
```

---

## 🤝 **Contributing**

We welcome contributions and new ideas!
To contribute:

1. Fork this repository.
2. Create a feature branch.
3. Commit and push your updates.
4. Open a pull request describing your changes.


## 🌟 **In Short**

JobHunter is a complete full-stack application built to showcase:

* **Spring Boot backend engineering**
* **React frontend integration**
* **Secure JWT authentication**
* **Modern REST API design**

