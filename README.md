# 🔐 Graph-Based Password Authentication System

## 📌 Project Overview

This project is a **Graphical Password Authentication System** developed using Django.
Instead of traditional text passwords, users authenticate by selecting specific points (graphical pattern) on an image.

---

## 🚀 Features

* 👤 User Registration & Login
* 🖼️ Image-based password system
* 🔒 Graphical (point-based) authentication
* 🗄️ MySQL database integration
* ⚡ Fast and secure login process

---

## 🛠️ Tech Stack

* **Backend:** Python, Django
* **Frontend:** HTML, CSS, JavaScript
* **Database:** MySQL
* **Connector:** PyMySQL

---

## 📂 Project Structure

GraphPassword/
│── GraphPassword/        # Main project folder
│── GraphPasswordApp/     # Application logic
│── templates/            # HTML files
│── static/               # CSS, JS
│── manage.py

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/GraphPassword.git
cd GraphPassword
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Setup database

* Open MySQL
* Create database:

```sql
CREATE DATABASE graphpassword;
```

### 5️⃣ Run server

```bash
python manage.py runserver
```

---

## 🌐 Usage

* Open browser: http://127.0.0.1:8000/
* Register a new user
* Select graphical password
* Login using selected pattern

---

## 📸 Screenshots

(Add screenshots here)

---

## 🔥 Future Enhancements

* Improve UI/UX
* Add encryption for password storage
* Deploy to cloud (Render/AWS)
* Add multi-factor authentication

---

## 👨‍💻 Author
Devender

---

## ⭐ Acknowledgment

This project is developed as part of academic learning and security system implementation.
