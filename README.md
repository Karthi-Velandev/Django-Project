# Django-Project

## 📝 Project Title:
Django Todo App with User Login and Admin Dashboard

## 🎯 Objective:
To create a web application using Django where:

Users can register, log in, and manage their own tasks (todos)

Admins (superusers) can view all users and their tasks

# 🔧 Key Features:
## ✅ User Functionality:
Register and log in securely using Django's auth system.

Access a personalized dashboard to view, create, delete, and toggle tasks.

Tasks are linked to the currently logged-in user only.

Users can only see and manage their own tasks.

## ✅ Admin Functionality:
After logging in, admins are shown an admin dashboard.

Admins can:

View a list of all registered users.

View every task in the system, along with who created it.

Admins cannot create tasks for other users (unless added later).

## ✅ Task Model:
Each task contains:

title – A short description.

completed – A checkbox for done/undone status.

user – Foreign key to the task creator.

## 🖥️ Technology Stack:
Backend: Django (Python)

Frontend: Django Templates with Bootstrap 5

Database: SQLite3 (default Django DB)

## 🔐 Authentication & Access Control:
Django’s built-in User model is used.

Pages are protected using @login_required.

Dashboard behavior changes based on whether the user is an admin or a regular user.

