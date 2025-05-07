# 📊 Attendance Management System (MEAN Stack)

<p align="center">
  <img src="https://th.bing.com/th/id/OIP.AeAOQVaFxhw31oFijfLVJQHaCn?rs=1&pid=ImgDetMain" alt="Attendance Banner" width="80%" />
</p>

A full-stack web application for managing student attendance efficiently using Angular, Node.js, Express, and MongoDB. It supports **three types of users** with distinct dashboards and permissions.

---

## 👥 User Roles & Features

### 🔑 Admin

* Add, delete, and manage:

  * 📚 Sections
  * 📘 Subjects
  * 👩‍🏫 Teachers
  * 👨‍🎓 Students
* Only the **Admin** can create Teacher and Student accounts initially.

### 👩‍🏫 Teacher

* ✅ Mark, edit, and print attendance.
* 📊 View dashboard with attendance summaries.
* 📣 Post notices for specific sections (visible to relevant students).

### 👨‍🎓 Student

* 📄 View detailed and summarized attendance records.
* 🔔 Read notifications/announcements by their teachers.

---

## 🧱 Tech Stack

| Layer          | Technologies Used                     |
| -------------- | ------------------------------------- |
| Frontend       | Angular • Chart.js • Bootstrap • SCSS |
| Backend        | Node.js • Express.js                  |
| Database       | MongoDB                               |
| Authentication | JWT (JSON Web Token)                  |

---

## ⚙️ Getting Started

Follow the steps below to run the application locally:

### 1️⃣ Clone the Repository

```git clone https://github.com/KarunyaChavan/AttendanceManagementSystem.git```<br>
```cd AttendanceManagementSystem```

### 2️⃣ Install Frontend Dependencies

```cd frontend```
```npm install --force```

### 3️⃣ Start the Frontend Server

```ng serve --open```

### 4️⃣ Start the Backend Server

Open a new terminal window:

```cd backend```
```npm install```
```node app.js```

---

## 📂 Project Structure

```
attendance-management-mean/
├── frontend/           → Angular Frontend
│   ├── src/
│   └── angular.json
├── backend/            → Node.js & Express Backend
│   ├── models/
│   ├── routes/
│   └── server.js
└── README.md
```

---

## 📌 Key Highlights

* Role-based login with JWT authentication
* Real-time attendance updates
* Dynamic Chart.js visualizations for Teachers
* Secure notice board system
* Print and export attendance records

---

## 📬 Contact

Have suggestions or issues? Feel free to reach out:

**📧** [karunyachavan84@outlook.com](mailto:karunyachavan84@outlook.com)
**🔗** [LinkedIn](https://linkedin.com/in/karunya-chavan-kc)
**💻** [GitHub](https://github.com/KarunyaChavan)

---

> Built with ❤️ using the MEAN stack for seamless academic attendance automation.
