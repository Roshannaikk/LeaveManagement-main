🚀 LeaveBot System

A modern Leave Management System built using microservices architecture. It helps companies manage employee leave requests, approvals, and notifications easily.

📌 Project Overview
🔹 What is LeaveBot?

LeaveBot is a system where:

Employees can apply for leave
Admins can approve or reject requests
Notifications (Email/SMS) are sent automatically

It makes leave management fast, organized, and user-friendly.

⭐ Key Features
🔐 Secure Login (JWT authentication)
👥 Employee Management (Add, update, delete employees)
📝 Leave Requests (Apply, approve, reject)
🔔 Notifications (Email & SMS alerts)
📊 Dashboard (Admin & Employee views)
📁 Logs (All notifications saved)
🏗️ System Architecture (Simple Explanation)

The system is divided into small services:

Frontend (React) → User interface
API Gateway → Controls all requests
Auth Service → Login & security
Employee Service → Employee data
Leave Service → Leave handling
Notification Service → Email & SMS

👉 Each service works independently but communicates using APIs.

🔄 How the System Works
1. Login
User enters email & password
System verifies and gives a token
User is redirected based on role
2. Apply Leave
Employee fills form
Leave is saved in database
Notification is sent to admin
3. Approve/Reject Leave
Admin reviews request
Approves or rejects
Employee gets notification
4. Add Employee
Admin adds new employee
System sends welcome email
🔧 Services Overview
1. API Gateway
Entry point for all requests
Routes requests to correct service
2. Auth Service
Handles login & security
Generates JWT token
3. Employee Service
Manages employee data
Add / Update / Delete employees
4. Leave Service
Handles leave requests
Tracks status (Pending, Approved, Rejected)
5. Notification Service
Sends Email & SMS
Saves logs in MongoDB
💻 Frontend

Built using:

React.js
Tailwind CSS
Pages:
Login Page
Admin Dashboard
Employee Dashboard
Apply Leave
View Leaves
Notification Logs
🚀 Setup (Simple Steps)
1. Clone Project
git clone <repo-url>
cd project-folder
2. Start Services
Notification Service
cd Services/Notification.API
npm install
npm start
API Gateway
cd Services/API.Gateway
npm install
npm start
Frontend
cd frontend-ui
npm install
npm start
3. Start Other Services
Run Auth (.NET)
Run Employee (.NET)
Run Leave (Python)
🔗 API Usage

All requests go through:

http://localhost:8080

Example:

POST /api/auth/login
POST /api/leave/apply
🔐 Authentication

Use JWT token in header:

Authorization: Bearer <token>
⚠️ Common Issues
❌ Email not sending
Check SMTP settings
Check password
❌ API not working
Make sure all services are running
❌ MongoDB error
Start MongoDB
Check connection string
💡 Why This Project is Good
Uses microservices (industry-level)
Multiple technologies used
Real-world problem solving
Scalable and modular design
📌 Conclusion

LeaveBot is a complete smart leave management system that:

Saves time
Improves organization
Automates communication
