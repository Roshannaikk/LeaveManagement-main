🚀 LeaveBot System

A microservices-based Leave Management System designed to manage employee leave requests, approvals, and notifications in an efficient and scalable way.

📌 Project Overview

LeaveBot System is a smart application that helps organizations:

Manage employee leave requests
Automate approval workflows
Send real-time notifications (Email/SMS)
Maintain complete records and logs

👉 The system is built Got you 👍 — I’ll upgrade your README with **perfect typography, clean spacing, professional GitHub style, icons, badges, and formatting** (ready to impress in viva + GitHub 🔥)

---

# 🚀 **LeaveBot System**

> A modern **Microservices-Based Leave Management Platform** with real-time notifications and scalable architecture.

---

<p align="center">
  <b>⚡ Smart • Scalable • Secure • Industry-Level Project ⚡</b>
</p>

---

## 🧭 **Overview**

**LeaveBot** is a smart system that helps organizations manage employee leave efficiently.

It allows:

* Employees to apply for leave
* Admins to approve/reject requests
* Automatic notifications via Email & SMS

💡 Built using **Microservices Architecture**, making it modular and production-ready.

---

## ✨ **Key Features**

| Feature                      | Description            |
| ---------------------------- | ---------------------- |
| 🔐 **Secure Authentication** | JWT-based login system |
| 👥 **Employee Management**   | Full CRUD operations   |
| 📝 **Leave Workflow**        | Apply, approve, reject |
| 🔔 **Notifications**         | Email & SMS alerts     |
| 📊 **Dashboard**             | Real-time insights     |
| 📁 **Audit Logs**            | Notification tracking  |

---

## 🏗️ **Architecture**

```
Frontend (React)
        │
        ▼
API Gateway (Node.js)
        │
 ┌──────┼────────┬──────────┬──────────┐
 ▼      ▼        ▼          ▼
Auth   Employee  Leave   Notification
(.NET) (.NET)  (Flask)   (Node.js)
        │
        ▼
   SQL Server       MongoDB
```

---

## ⚙️ **Tech Stack**

| Layer               | Technology                  |
| ------------------- | --------------------------- |
| 🎨 Frontend         | React.js, Tailwind CSS      |
| 🔗 API Gateway      | Node.js (Express)           |
| 🔐 Auth Service     | .NET Core                   |
| 👥 Employee Service | .NET Core                   |
| 📝 Leave Service    | Python (Flask)              |
| 🔔 Notification     | Node.js, Nodemailer, Twilio |
| 🗄️ Database        | SQL Server, MongoDB         |

---

## 🔄 **System Workflow**

### 🔑 1. Login

* User enters credentials
* Token generated (JWT)
* Redirect to dashboard

---

### 📝 2. Apply Leave

* Employee submits request
* Data stored in database
* Admin gets notification

---

### ✅ 3. Approval Process

* Admin approves/rejects
* Status updated
* Employee notified

---

### 👤 4. Add Employee

* Admin creates employee
* Welcome email sent

---

## 🧩 **Microservices Breakdown**

### 📡 API Gateway

| Property | Value                   |
| -------- | ----------------------- |
| Port     | 8080                    |
| Role     | Central request handler |

---

### 🔐 Auth Service

| Feature  | Details        |
| -------- | -------------- |
| Port     | 5265           |
| Role     | Authentication |
| Security | JWT            |

---

### 👥 Employee Service

| Feature | Details          |
| ------- | ---------------- |
| Port    | 5219             |
| Role    | Manage employees |

---

### 📝 Leave Service

| Feature | Details                       |
| ------- | ----------------------------- |
| Port    | 5555                          |
| Role    | Leave processing              |
| Status  | Pending / Approved / Rejected |

---

### 🔔 Notification Service

| Feature  | Details     |
| -------- | ----------- |
| Port     | 5004        |
| Role     | Email & SMS |
| Database | MongoDB     |

---

## 💻 **Frontend**

| Feature   | Details      |
| --------- | ------------ |
| Framework | React.js     |
| Styling   | Tailwind CSS |
| API       | Axios        |

### 📄 Pages

* Login
* Admin Dashboard
* Employee Dashboard
* Apply Leave
* Leave History
* Notification Logs

---

## 🚀 **Getting Started**

### 📥 Clone Repository

```bash
git clone <repo-url>
cd LeaveBot
```

---

### ▶️ Run Services

#### 🔔 Notification Service

```bash
cd Services/Notification.API
npm install
npm start
```

#### 📡 API Gateway

```bash
cd Services/API.Gateway
npm install
npm start
```

#### 💻 Frontend

```bash
cd frontend-ui
npm install
npm start
```

---

### ⚡ Start Backend Services

* Run Auth Service (.NET)
* Run Employee Service (.NET)
* Run Leave Service (Python)

---

## 🔗 **API Reference**

| Method | Endpoint                    | Description   |
| ------ | --------------------------- | ------------- |
| POST   | `/api/auth/login`           | Login         |
| POST   | `/api/leave/apply`          | Apply leave   |
| GET    | `/api/employees`            | Get employees |
| PUT    | `/api/leave/{id}/approve`   | Approve leave |
| POST   | `/notifications/send-email` | Send email    |

---

## 🔐 **Authentication**

```bash
Authorization: Bearer <your-token>
```

---

## 🗄️ **Database Design**

### 🧾 SQL Server

| Table      | Purpose          |
| ---------- | ---------------- |
| users_auth | Login data       |
| employees  | Employee records |
| leaves     | Leave requests   |

---

### 📦 MongoDB

| Collection        | Purpose          |
| ----------------- | ---------------- |
| notification_logs | Email & SMS logs |

---

## ⚠️ **Troubleshooting**

| Issue             | Solution                    |
| ----------------- | --------------------------- |
| Email not working | Check SMTP credentials      |
| API errors        | Ensure services are running |
| MongoDB error     | Start MongoDB               |
| Login failed      | Verify JWT config           |

---

## 💡 **Why LeaveBot?**

✔ Microservices architecture
✔ Real-world application
✔ Scalable design
✔ Clean UI + backend integration
✔ Industry-ready project

---

## 🔮 **Future Enhancements**

* 🤖 AI-based leave prediction
* 📱 Mobile app
* ☁️ Cloud deployment (AWS / Azure)
* 📊 Advanced analytics

---

## 🏁 **Conclusion**

**LeaveBot** is a powerful and scalable system that simplifies leave management by combining:

* Automation
* Security
* Modern architecture

---

<p align="center">
  ⭐ If you like this project, consider giving it a star!
</p>

---
