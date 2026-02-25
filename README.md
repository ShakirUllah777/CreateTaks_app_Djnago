# 📝 CreateTask – Django Task Management System

A clean and simple **Task Management Web Application** built with **Django** that allows users to perform full **CRUD operations** (Create, Read, Update, Delete) on tasks.

This project focuses on backend logic using Django and frontend rendering using Django Templates for a neat and user-friendly interface.

---

## 🚀 Features

✅ Create new tasks
✅ View all tasks
✅ Update/Edit existing tasks
✅ Delete tasks
✅ Clean and responsive UI using Django Templates
✅ Organized backend logic using Django Views & Models
✅ Simple and beginner-friendly project structure

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS (Django Templates)
* **Database:** SQLite (default Django database)
* **Version Control:** Git

---

## 📂 Project Structure

```
createtask/
│
├── manage.py
├── createtask/
│   ├── settings.py
│   ├── urls.py
│
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│
└── db.sqlite3
```

---

## 🧠 How It Works

* The **Model** defines the Task structure (title, description, etc.)
* The **Views** handle the business logic for CRUD operations
* The **Templates** render dynamic content to the browser
* URLs are mapped properly to connect frontend and backend

---

## ⚙️ Installation Guide

Follow these steps to run the project locally:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ShakirUllah777/CreateTaks_app_Djnago.git
cd createtask
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install django
```

### 4️⃣ Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run the Server

```bash
python manage.py runserver
```

Now open your browser and go to:

```
http://127.0.0.1:8000/
```

---

## 📌 CRUD Operations Explained

| Operation  | Description               |
| ---------- | ------------------------- |
| **Create** | Add a new task            |
| **Read**   | View list of all tasks    |
| **Update** | Edit an existing task     |
| **Delete** | Remove a task permanently |

---

## 🎯 Learning Objectives

This project helps you understand:

* Django project structure
* Models & Migrations
* Function-Based or Class-Based Views
* URL routing
* Template rendering
* Basic CRUD logic
* Clean code organization

---

## 🌟 Future Improvements

* User Authentication (Login/Register)
* Task Status (Completed/Pending)
* Search & Filter tasks
* REST API version using Django REST Framework
* Deployment on Heroku / PythonAnywhere

---

## 👨‍💻 Author

**Shakir Ullah**
Django Backend Developer

---

## 📄 License

This project is open-source and available for learning purposes.

