
# 🎓 Student Performance & Placement Connect

A **full-stack web platform** designed to manage student academics and placement activities. The system helps students track their performance, monitor job applications, and stay updated on placement opportunities, while administrators can easily publish job roles, filter candidates, and maintain placement records.

---

## 📚 Table of Contents

* 🔎 Introduction
* ✨ Key Features
* 🛠️ Technology Stack
* 🌐 Deployment
* 🎥 Demo Video
* 🚀 Setup & Installation

---

## 🔎 Introduction

The **Placement Connect System** is a role-based application that simplifies how colleges handle student records and placement activities. Students can apply for jobs, update their application status, and view leaderboards, while the placement cell can post jobs, review applications, and manage student performance data from a single dashboard.

---

## ✨ Key Features

### 🎓 Student Panel

* Secure sign-up and login
* Manage personal details, skills, and academic information (CGPA, etc.)
* Explore job postings with eligibility and role details
* Apply for jobs and update status (Applied, Selected, Rejected)
* Dashboard to track all applications
* View ranking of top-placed students

### 🛠️ Admin Panel

* Add and update job opportunities with criteria
* Review and track student applications
* Filter candidates based on requirements
* Manage job records and placement statistics

---

## 🛠️ Technology Stack

| **Layer**      | **Technologies Used**                                              |
| -------------- | ------------------------------------------------------------------ |
| Frontend       | React.js, Material UI, Axios                                       |
| Backend        | Node.js, Express.js                                                |
| Database       | MongoDB with Mongoose                                              |
| Authentication | Custom MongoDB-based authentication                                |
| API            | RESTful APIs with Axios communication                              |
| Tools          | body-parser, cors, dotenv, nodemon, Postman, VS Code, Git & GitHub |
| Deployment     | Render                                                             |

---

## 🌐 Deployment

🔗 **Live Application**:(https://placement-connect-pnkr.onrender.com/)

🎥 **Video Walkthrough**: https://www.linkedin.com/posts/harshini-v-7977182a9_excited-to-announce-this-is-my-small-project-activity-7346909554330255361-u3iH?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEpSr2MBaNqvVo7exXHCrnBVDgQZhU5NhaA
---

## 🚀 Setup & Installation

### 🔧 Requirements

Ensure these are installed:

* Node.js & npm
* MongoDB (local or Atlas)
* VS Code
* Git

### 📦 Steps

1. **Clone the repository**

   ```bash
   git clone https://github.com/009-Harshini/placement_connect.git
   cd placement_connect
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set environment variables**
   Create a `.env` file in the root folder with:

   ```env
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/placement_db
   JWT_SECRET=your_custom_secret
   ```

4. **Start MongoDB**

   ```bash
   mongod
   ```

5. **Run the backend server**

   ```bash
   npm start
   ```

6. **Run the frontend**
   Navigate to the frontend folder and start React:

   ```bash
   npm start
   ```

### 🌐 Access

* App: (http://localhost:3000)
* API:(http://localhost:5000/api)

---

👩‍💻 Author

HARSHINI V

Developed as part of an academic project.

📎https://github.com/009-Harshini/placement_connect.git

📎 LinkedIn - https://www.linkedin.com/posts/harshini-v-7977182a9_excited-to-announce-this-is-my-small-project-activity-7346909554330255361-u3iH?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEpSr2MBaNqvVo7exXHCrnBVDgQZhU5NhaA
