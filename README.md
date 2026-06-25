# 🎓 Django Student Management System

A modern, full-stack **Student Management System** built with **Django**, **Django REST Framework**, and **Bootstrap**. The application streamlines academic administration by providing modules for student records, course management, attendance, fee tracking, examination results, and user authentication through an intuitive dashboard.

---

## ✨ Key Features

### 🔐 Authentication & Security

* Secure Login & Logout
* Django Authentication System
* JWT Authentication using SimpleJWT
* Protected Routes
* Admin Dashboard

### 👨‍🎓 Student Management

* Add New Students
* Update Student Details
* Delete Student Records
* Search Students
* View Student Profiles

### 📚 Course Management

* Create Courses
* Update Course Information
* Assign Courses to Students
* View Available Courses

### 📅 Attendance Management

* Mark Daily Attendance
* View Attendance Records
* Attendance Summary

### 💰 Fee Management

* Record Student Fees
* Track Pending Payments
* Fee History
* Payment Status

### 📝 Result Management

* Add Student Marks
* Calculate Results
* Display Academic Performance
* View Result History

### 📊 Dashboard

* Interactive Charts (Chart.js)
* Student Statistics
* Attendance Analytics
* Fee Collection Overview
* Responsive Cards

### 🔍 Additional Features

* Search & Filtering
* Responsive Bootstrap UI
* REST API Support
* SQLite Database
* Image Upload Support
* Static File Management

---

# 🛠 Tech Stack

| Category       | Technologies                         |
| -------------- | ------------------------------------ |
| Backend        | Django 5.x                           |
| API            | Django REST Framework                |
| Authentication | JWT (SimpleJWT)                      |
| Frontend       | HTML5, CSS3, Bootstrap 5, JavaScript |
| Charts         | Chart.js                             |
| Database       | SQLite                               |
| Image Handling | Pillow                               |
| Static Files   | WhiteNoise                           |
| Filtering      | django-filter                        |

---

# 📂 Project Structure

```text
gyan_uday/
│
├── accounts/
├── attendance/
├── courses/
├── dashboard/
├── fees/
├── results/
├── students/
├── templates/
├── static/
├── media/
├── manage.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/amritanshu1968-wq/student-management-system.git
```

```bash
cd student-management-system
```

---

## 2. Create Virtual Environment

Windows

```bash
python -m venv env
```

Activate

```bash
env\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv env
```

```bash
source env/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Apply Database Migrations

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

---

## 5. Create Admin User

```bash
python manage.py createsuperuser
```

---

## 6. Start Development Server

```bash
python manage.py runserver
```

---

# 🌐 Local URLs

| Service     | URL                              |
| ----------- | -------------------------------- |
| Home        | http://127.0.0.1:8000            |
| Dashboard   | http://127.0.0.1:8000/dashboard/ |
| Admin Panel | http://127.0.0.1:8000/admin/     |
| API         | http://127.0.0.1:8000/api/       |

---

# 📡 REST API

Example endpoints

```text
/api/students/
/api/courses/
/api/attendance/
/api/results/
/api/token/
/api/token/refresh/
```

# 🚀 Future Enhancements

* Student Portal
* Teacher Portal
* Parent Dashboard
* Email Notifications
* SMS Alerts
* PDF Report Generation
* Excel Export
* Role-Based Permissions
* Dark Mode
* Tailwind CSS UI
* Docker Deployment
* PostgreSQL Support
* AWS Deployment
* CI/CD Pipeline

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# 📄 License

This project is developed for educational and portfolio purposes.

---

# 👨‍💻 Author

**Amritanshu Shukla**

B.Tech Computer Science Engineering (IoT)

Aspiring Software Developer | Django Developer | Python Enthusiast

LinkedIn: *(Add your LinkedIn URL)*

GitHub: *(Add your GitHub URL)*

Email: *(Add your email address)*
