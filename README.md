# Employee Management System (Django)

A simple Employee Management System built using Django. This project allows users to manage employee records with authentication (login/logout) and CRUD operations.
## 📦 Download

Download the complete project from below:

* [Download Employee Project (ZIP)](https://github.com/vijayvs2341/Employee-Management-System-Django-/releases/download/v1.0.0/employee_project.zip)

---
## 🚀 Features

* User Authentication (Login & Logout)
* Create Employee Records
* View Employee List
* Update Employee Details
* Delete Employee Records
* Protected Routes using Login Required
* Django Messages Framework for alerts

---

## 🛠️ Tech Stack

* Python
* Django
* SQLite (default database)
* HTML (Templates)
* Bootstrap (optional for styling)

---

## 📁 Project Structure

```
employee_project/
│
├── employee_project/      # Main project settings
├── employees/             # App for employee management
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   ├── templates/
│   │   └── employees/
│   │       ├── login.html
│   │       ├── employee_list.html
│   │       └── employee_form.html
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/employee_project.git
cd employee_project
```

2. Create virtual environment

```bash
python -m venv venv
```

3. Activate virtual environment

* Windows:

```bash
venv\Scripts\activate
```

* Mac/Linux:

```bash
source venv/bin/activate
```

4. Install dependencies

```bash
pip install django
```

5. Apply migrations

```bash
python manage.py migrate
```

6. Create superuser (optional)

```bash
python manage.py createsuperuser
```

7. Run the server

```bash
python manage.py runserver
```

---

## 🔐 Authentication

* Users must log in to access employee features
* Unauthorized users are redirected to login page

---

## 📌 URLs Overview

| URL             | Description     |
| --------------- | --------------- |
| `/login/`       | Login page      |
| `/logout/`      | Logout          |
| `/`             | Employee list   |
| `/create/`      | Add employee    |
| `/update/<id>/` | Update employee |
| `/delete/<id>/` | Delete employee |

---

## 📸 Screenshots

(Add screenshots here if you want)

---

## 🤝 Contributing

Feel free to fork this repository and contribute!

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Vijay selvan
GitHub: https://github.com/vijayvs2341

---
