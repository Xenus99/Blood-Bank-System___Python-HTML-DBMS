# 🩸 Blood Bank Management System

A web-based application built with **Django**, **HTML/CSS**, and **SQLite** to manage blood donation, donor registration, and blood requests efficiently. The system allows hospitals, administrators, and donors to interact through a unified platform.

---

## 🚀 Features

- 🧑‍💻 User registration & login system
- 🧾 Donor profile creation and management
- 📄 Blood request submission and tracking
- 📋 Admin dashboard for managing donors and requests
- 🔍 Search functionality to find available blood types
- 🖼️ Profile picture upload (via `ImageField`)
- 🎨 Responsive UI with HTML templates

---

## ⚙️ Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS
- **Database:** SQLite (via Django ORM)
- **Image Uploads:** Pillow (Python Imaging Library)

---

## 🛠️ Setup Instructions

### Prerequisites
- Python 3.8+
- Conda (or pip/virtualenv)

### Step 1: Clone and Setup Environment

```bash
git clone https://github.com/yourusername/blood-bank-system.git
cd blood-bank-system
pip install -r requirements.txt
```

### Step 2: Migrate Database

```bash
python manage.py migrate
```

### Step 3: Run the Server

```bash
python manage.py runserver
```

### Step 4 (Optional): Create Admin User

```bash
python manage.py createsuperuser
```

## 📁 Project Structure

```bash
Blood-Bank-System/
├── manage.py
├── db.sqlite3
├── bloodbank/                # Django project settings
├── blood_app/                # Main application
│   ├── models.py             # Models (UserExtend, BloodGroup, etc.)
│   ├── views.py              # Views and logic
│   ├── templates/            # HTML templates
│   └── migrations/
```
