# schoolms
This is a school management system with AI-Driven functionalities.

# 🏫 School Management System

A secure, full-stack school management system built with Django and ReactJS. Designed to streamline academic operations, enhance communication, and ensure data integrity across school departments.

---

## 🚀 Features

- 🔐 Secure login and role-based access (Admin, Teacher, Student)
- 📚 Course and subject management
- 📝 Attendance and grading system
- 📊 Performance analytics and dashboards
- 📧 Email notifications and messaging
- 🗂️ Document uploads and student records
- ⚠️ Phishing-safe UI with modal warnings for risky actions

---

## 🛠️ Tech Stack

| Layer       | Technology         |
|------------|--------------------|
| Backend     | Django, Django REST Framework |
| Frontend    | ReactJS, Webpack |
| Database    | PostgreSQL (or SQLite for dev) |
| DevOps      | GitHub Actions, Docker |
| Security    | Django Axes, CORS, HTTPS |
| Testing     | Pytest, Coverage |

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/CyberPriest/schoolms.git
cd schoolms

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the server
python manage.py migrate
python manage.py runserver
