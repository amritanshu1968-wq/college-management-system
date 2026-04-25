# 🎓 Django Student Management System

A full-stack **Student Management System** built using **Django, Django REST Framework, and Bootstrap**.
This project provides a modern dashboard to manage students, courses, attendance, fees, and results with authentication support.

---

## 🚀 Features

* 🔐 User Authentication (Login / Logout / JWT Support)
* 📊 Interactive Dashboard with Charts (Chart.js)
* 👨‍🎓 Student Management (Add, View, Search)
* 📚 Course Management
* 📅 Attendance Tracking
* 💰 Fee Management System
* 📝 Result & Marks Tracking
* 🔍 Search & Filtering
* 📱 Responsive UI (Bootstrap)
* ⚡ REST API Support (DRF)

---

## 🛠 Tech Stack

* **Backend:** Django, Django REST Framework
* **Frontend:** HTML, CSS, Bootstrap, JavaScript
* **Database:** SQLite (default)
* **Authentication:** JWT (SimpleJWT)
* **Other Tools:** django-filter, Pillow, WhiteNoise

---

## 📁 Project Structure

```
gyan_uday/
│
├── accounts/
├── students/
├── courses/
├── attendance/
├── fees/
├── results/
├── dashboard/
├── templates/
├── static/
├── manage.py
```

---

## ⚙️ Installation & Setup

### 2️⃣ Create virtual environment

```
python -m venv env
```

Activate it:

**Windows (PowerShell):**

```
.\env\Scripts\Activate
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Apply migrations

```
python manage.py migrate
```

---

### 5️⃣ Create superuser

```
python manage.py createsuperuser
```

---

### 6️⃣ Run server

```
python manage.py runserver
```

---

## 🌐 Access the Project

* Dashboard: http://127.0.0.1:8000/dashboard/
* Admin Panel: http://127.0.0.1:8000/admin/


## 💡 Future Improvements

* 🔥 Advanced analytics with graphs
* 📱 Mobile responsive UI (Tailwind upgrade)
* 🌍 Deployment (Render / AWS)
* 📊 Export reports (PDF/Excel)
* 👥 Role-based access (Admin / Student)



---
