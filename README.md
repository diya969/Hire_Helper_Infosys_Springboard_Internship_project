# 🧑‍🤝‍🧑 Hire-A-Helper (Personal Copy)

> **Note:** This repository is a personal copy of a team project completed during the Infosys Springboard Internship. The original project was developed collaboratively by a team of five members. My primary contribution was frontend development using React, TypeScript, and Tailwind CSS.

## 👩‍💻 My Contribution

* Developed frontend user interfaces using React and TypeScript.
* Built responsive pages and reusable UI components.
* Designed and implemented authentication-related screens.
* Developed task feed, dashboard, profile, and settings pages.
* Integrated frontend components with backend APIs.
* Collaborated with team members throughout the project lifecycle.

## 🔗 Original Team Repository

Repository: https://github.com/Lakshmi-Boora/Internship_Infosys_2025_Hire_A_Helper_Team_04

## 👥 Team Members

* Anuj Gaud
* Lakshmi Boora
* Dinesh Karthick A
* Krishna Deepika K
* Nunna Ishwarya

---

# 🌟 Introduction

Hire-A-Helper is a full-stack web application designed to simplify collaboration between people who need assistance and those willing to help.

Users can post tasks, request to help with tasks, receive notifications, and manage their activities through an intuitive dashboard.

Built using the MERN Stack with TypeScript, the platform focuses on usability, collaboration, and efficient task management.

---

# ✨ Features

## 🔐 Authentication

* User Registration and Login
* Email OTP Verification
* Secure JWT Authentication
* Password Reset Functionality

## 🧾 Task Management

* Create New Tasks
* View Personal Tasks
* Browse Community Task Feed
* Manage Task Status

## 🙋 Request Handling

* Send Requests to Help
* Accept or Reject Requests
* Track Request Status
* Notification-based Updates

## 🧑‍💼 Profile Management

* Update Profile Information
* Upload Profile Picture
* Manage Personal Settings

## 🖥️ Dashboard

* User-Friendly Interface
* Responsive Design
* Easy Navigation

---

# ⚙️ Tech Stack

| Layer             | Technologies                        |
| ----------------- | ----------------------------------- |
| Frontend          | React, TypeScript, Tailwind CSS     |
| Backend           | Node.js, Express.js                 |
| Database          | MongoDB, Mongoose                   |
| Authentication    | JWT, bcrypt                         |
| File Upload       | Multer                              |
| Email Service     | Nodemailer                          |
| Development Tools | Git, GitHub, VS Code, Postman, Vite |

---

# 🧩 System Workflow

User Registration/Login

⬇️

Email OTP Verification

⬇️

Dashboard Access

⬇️

Create Task

⬇️

Task Appears in Feed

⬇️

Other Users Send Requests

⬇️

Task Owner Receives Notification

⬇️

Accept / Reject Request

⬇️

Task Collaboration

---

# 🗃️ Database Collections

## 👤 User

Stores:

* User Information
* Authentication Details
* Profile Information
* OTP Verification Data

## 📋 Task

Stores:

* Task Details
* Location Information
* Status Tracking
* Task Ownership

## 🤝 Request

Stores:

* Helper Requests
* Request Status
* Request Messages

## 🔔 Notification

Stores:

* User Notifications
* Read/Unread Status

## ✅ AcceptedTask

Stores:

* Accepted Tasks
* Completion Status

---

# 🌐 API Modules

## Authentication APIs

* Register User
* Verify OTP
* Resend OTP
* Login
* Forgot Password
* Reset Password
* Logout

## Task APIs

* Create Task
* Update Task
* Delete Task
* Get Task Feed
* Get My Tasks

## Request APIs

* Send Request
* Accept Request
* Reject Request
* View Requests

## Notification APIs

* View Notifications
* Mark Notification as Read

## Settings APIs

* Update Profile
* Update Password
* Update Profile Picture

---

# 🛠️ Installation & Setup

## Clone Repository

```bash
git clone <your-repository-url>
cd Hire_Helper_Infosys_Springboard_Internship_project
```

## Backend Setup

```bash
cd backend
npm install
npm run dev
```

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=2000
NODE_ENV=development

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

EMAIL_USER=your_gmail_address

EMAIL_PASS=your_app_password
```

---

# 🌐 Run Application

Frontend:

```bash
http://localhost:5173
```

Backend:

```bash
http://localhost:2000
```

---

# 🚀 Future Enhancements

* Real-Time Chat System
* Payment Integration
* User Rating and Review System
* Mobile Application
* Advanced Search and Filtering
* Push Notifications

---

# 📌 Disclaimer

This repository is maintained as a personal copy of a team project completed during the Infosys Springboard Internship. Credit for the project belongs to all team members listed above. This repository is intended for learning, portfolio, and reference purposes.

