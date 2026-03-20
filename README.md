# 🏥 Hospital Management System (Python + MySQL)

A menu-driven Hospital Management System developed using Python and MySQL, designed to manage patients, staff, and medicine inventory efficiently through a command-line interface.

This project is suitable for college mini-projects, DBMS labs, and Python–MySQL integration practice.

--- 

## ✨ Features
### 👨‍⚕️ Patient Management
- Add new patient records
- Search patient (all or by ID)
- Update patient details (name, age, diagnosis)
- Add discharge date
- Delete patient records

### 🧑‍💼 Staff Management
- Add new staff members
- Search staff by ID
- Update staff details (name, position, department)
- Delete staff records

### 💊 Medicine Stock Management
- Add new medicines
- Search medicine by ID
- Update quantity and unit price
- Delete medicine records

### 🔐 Security
- Password-protected system access

---

## 🛠️ Technologies Used
- Python 3
- MySQL
- mysql-connector-python

---

## 📁 Project Structure
```bash
Hospital-Management-System/
│
├── HOSPITAL.py          # Main Python program
├── README.md            # Project documentation
└── RESULT
```

---

## ⚙️ Requirements
- Software
- Python 3.x
- MySQL Server
- MySQL Workbench (recommended)
- Python Library :
```bash
pip install mysql-connector-python
```
---

## 🗄️ Database Setup

- Open MySQL and create the database:
- CREATE DATABASE hospital_management;
- Update database credentials in main() function:
```bash
host = "localhost"
user = "root"
password = "YOUR_PASSWORD"
database = "hospital_management"
```

---

## ⚠️ Important:
> Do NOT upload real database passwords to public repositories.

---

## ▶️ How to Run the Project
```bash
python HOSPITAL.py
```

### 🔑 Login Details

Password: HOSPITAL

### 📋 Menu Overview
```bash
Main Menu
A - Patient Database
B - Staff Database
C - Medicine Database
D - Exit
```

Each section provides options for Add, Search, Update, Delete, and Exit.

---

## 🧠 Concepts Used
- Object-Oriented Programming (OOP)
- MySQL database integration
- CRUD operations
- Exception handling
- Menu-driven CLI system

---

## 🚧 Known Limitations

- Command-line interface only
- No user roles (admin/user)
- No data validation for duplicate IDs
- Password is hardcoded

--- 

## 🔮 Future Enhancements

- GUI using Tkinter / PyQt
- Role-based authentication
- Input validation & error handling
- Report generation
- Billing module
- Backup & restore functionality

--- 

## 👨‍💻 Author

Piyush Sharma
B.Tech Student | Python | DBMS | Software Development
