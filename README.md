
# 🏫 School Management System (Django)

A full-featured **School Management System** built with Django. This web-based application helps administrators manage students, staff, classes, attendance, results, and more in a structured way.

![image](https://github.com/user-attachments/assets/09a97d5a-96e1-4e43-9a7b-d7604e121d7b)


---

## ✨ Features

- 👩‍🎓 Student Registration & Management
- 🧑‍🏫 Teacher & Staff Management
- 🏫 Class Scheduling and Organization
- 📚 Subject Allocation
- 📊 Student Results and Grades
- 📅 Attendance Tracking
- 🔐 User Authentication with Login System
- 🛠 Admin Panel for Superusers
- 🌐 Web-based interface using HTML, CSS, and Bootstrap

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Django** (Web framework)
- **SQLite3** (Default DB; can be swapped with PostgreSQL or MySQL)
- **HTML/CSS + Bootstrap** (Frontend)

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Kalharapasan/school_management_Django.git
cd school_management_Django


# Create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser (admin)
python manage.py createsuperuser

# Start the development server
python manage.py runserver
```

---

## 🌐 Accessing the App

- Visit `http://127.0.0.1:8000/` for the frontend
- Visit `http://127.0.0.1:8000/admin/` for the Django Admin Panel

---

## 📁 Folder Structure

```
school-management-django/
├── school/               # Django app
├── static/               # CSS, JS, images
├── templates/            # HTML templates
├── db.sqlite3            # SQLite database
├── manage.py
└── README.md
```

---

## ✅ TODO (Future Enhancements)

- [ ] Add timetable generator
- [ ] SMS/email notification system
- [ ] Student/parent portal
- [ ] Attendance using QR or biometric

---

## 📃 License

This project is licensed under the **MIT License**.

---

> Built with ❤️ using Django
