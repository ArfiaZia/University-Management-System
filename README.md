# University Management System

A comprehensive web-based **University Management System** developed using **Flask** and **MySQL**. The system provides a centralized platform for managing students, departments, attendance records, and user authentication while supporting role-based access control for administrators and students.

This project was developed as part of a **Database Management Systems (DBMS)** academic project and demonstrates full-stack web development concepts including database integration, authentication, authorization, and CRUD operations.

---

# Features

## Authentication System

- User Registration
- User Login & Logout
- Session Management
- Secure User Authentication

## Role-Based Access Control

- Admin Dashboard
- Student Dashboard
- Admin-only operations
- Student-specific access permissions

## Student Management

- Add Student Records
- Edit Student Information
- Delete Student Records
- View Student Details
- Search Student Information

## Department Management

- Create Departments
- Manage Academic Departments
- Department Assignment for Students

## Attendance Management

- Record Student Attendance
- View Attendance Records
- Attendance Tracking System

## Database Features

- MySQL Database Integration
- SQLAlchemy ORM
- Relational Database Design
- Data Persistence

## User Interface

- Responsive Web Interface
- HTML Templates
- CSS Styling
- JavaScript Interactivity
- Flash Message Notifications

---

# Technologies Used

## Backend

- Python
- Flask
- Flask-SQLAlchemy
- Flask-Login

## Frontend

- HTML5
- CSS3
- JavaScript

## Database

- MySQL
- phpMyAdmin
- XAMPP Server

## Development Tools

- Visual Studio Code
- Git
- GitHub

---

# Installation Guide

## Prerequisites

Before running the project, make sure the following are installed:

- Python 3.x
- XAMPP
- MySQL
- Git

---

# Project Setup

## Step 1: Clone Repository

```bash
git clone https://github.com/your-username/university-management-system.git
cd university-management-system
```

## Step 2: Install Required Packages

```bash
pip install flask
pip install flask-sqlalchemy
pip install flask-login
pip install pymysql
```

## Step 3: Start XAMPP

Open XAMPP Control Panel and start:

- Apache
- MySQL

## Step 4: Import Database

1. Open phpMyAdmin
2. Create a database named:

```sql
sms
```

3. Import the provided SQL file:

```text
SMS SQL DATABASE.sql
```

## Step 5: Configure Database Connection

Verify the database connection in:

```python
main.py
```

```python
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+pymysql://root:@localhost:3306/sms'
```

Adjust username or password if required.

## Step 6: Run Application

```bash
python main.py
```

## Step 7: Open Browser

Visit:

```text
http://127.0.0.1:5000
```

---

# Project Structure

```text
University-Management-System/
│
├── main.py
├── SMS SQL DATABASE.sql
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── student.html
│   ├── studentdetails.html
│   ├── attendance.html
│   ├── department.html
│   ├── student_dashboard.html
│   └── other templates
│
├── static/
│   ├── css
│   ├── javascript
│   └── images
│
└── README.md
```

---

# System Modules

## Admin Module

- Manage Students
- Manage Departments
- Manage Attendance
- View Student Records
- Edit Student Records
- Delete Student Records

## Student Module

- Login to Personal Dashboard
- View Personal Information
- View Attendance Details

---

# Future Enhancements

- Password Encryption
- Faculty Management Module
- Course Registration System
- GPA Calculation
- Fee Management System
- Email Notifications
- Dashboard Analytics
- Multi-Role Authentication



# Authors

## 1. Abdul Moeed
## 2. Arfia Zia

### Institute

Pak Austria Fachhochschule Institute of Applied Sciences

---

# 📄 License

This project is licensed under the MIT License.

---

# Educational Purpose

This project was developed for academic learning and demonstrates practical implementation of **Database Management Systems (DBMS)**, **Web Development**, **Authentication Systems**, and **Role-Based Access Control (RBAC)** using **Flask** and **MySQL**.
