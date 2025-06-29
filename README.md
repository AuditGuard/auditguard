
# 📊 AuditGuard Backend

![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

**AuditGuard** is a backend server that fetches security policy scripts from a centralized database, executes them on the user's system, and generates audit reports in various formats — **HTML**, **CSV**, and **PDF**.

The application also provides advanced features like **audit scheduling**, **customized policy selection**, and **automated reporting**.

---

## 🚀 Features

- 🔐 Fetches audit policies dynamically based on the user's system configuration.
- 📜 Executes policy scripts locally on the client system.
- 📊 Generates detailed reports in **HTML**, **CSV**, and **PDF** formats.
- 📅 Supports **scheduling audits** for future execution.
- 🎛️ Allows **customization of policy sets** based on user preferences.
- ⚙️ Modular and scalable Django-based backend system.

---

## 📦 Run Locally

Follow these steps to set up and run the project on your local machine:

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sathyamkumar/auditguard-backend.git
```

### 2️⃣ Navigate to the project directory

```bash
cd auditguard-backend
```

### 3️⃣ Create and activate a Python virtual environment

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
# OR
source venv/bin/activate  # For macOS/Linux
```

### 4️⃣ Install project dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Run database migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Start the development server

```bash
python manage.py runserver
```

The server will start at `http://127.0.0.1:8000/` by default.

---
