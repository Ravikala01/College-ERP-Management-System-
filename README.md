# College-ERP-Management-System-
A web-based Enterprise Resource Planning (ERP) system developed using PHP and MySQL. This project provides a centralized platform to manage student records, faculty data, and administrative tasks with role-based secure login functionality.

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| PHP | Server-side programming |
| MySQL | Database management |
| HTML | Web page structure |
| CSS | Styling and design |
| XAMPP | Local web server environment |

---

## 📋 Features

- ✅ Role-based secure login (Administrator, Faculty, Student)
- ✅ Admin can manage student and faculty records
- ✅ Faculty can view and update student results
- ✅ Students can view their profile and results
- ✅ Digital result generation with grade calculation
- ✅ Replaces manual paper-based record system
- ✅ Centralized MySQL database for all records
- ✅ Responsive and clean UI using HTML and CSS

---

## 👥 User Roles

| Role | Access |
|------|--------|
| Administrator | Full access — manage students, faculty, results |
| Faculty | View and update student results |
| Student | View own profile and results |

---

## 🎓 Grade Calculation System

| Marks | Grade |
|-------|-------|
| 90 - 100 | O (Outstanding) |
| 80 - 89 | A+ (Excellent) |
| 70 - 79 | A (Very Good) |
| 60 - 69 | B+ (Good) |
| 50 - 59 | B (Above Average) |
| 40 - 49 | C (Average) |
| Below 40 | F (Fail) |

---

## 📁 Project Structure
College-ERP-Management-System/
│
├── index.php              # Login page
├── admin/
│   ├── dashboard.php      # Admin dashboard
│   ├── manage_students.php
│   ├── manage_faculty.php
│   └── manage_results.php
├── faculty/
│   ├── dashboard.php      # Faculty dashboard
│   └── update_results.php
├── student/
│   ├── dashboard.php      # Student dashboard
│   └── view_results.php
├── includes/
│   ├── db_connect.php     # Database connection
│   └── functions.php      # Common functions
├── css/
│   └── style.css          # Stylesheet
└── README.md              # Project documentation
---

## ⚙️ How to Run

### Prerequisites
- XAMPP installed on your system
- Web browser (Chrome/Firefox)

### Installation Steps

**Step 1 — Install XAMPP**
- Download XAMPP from [apachefriends.org](https://www.apachefriends.org)
- Install and open XAMPP Control Panel
- Start **Apache** and **MySQL**

**Step 2 — Set up the Project**
- Download or clone this repository
- Copy the project folder to:
C:/xampp/htdocs/College-ERP-Management-System
**Step 3 — Set up the Database**
- Open browser and go to: `http://localhost/phpmyadmin`
- Create a new database called `college_erp`
- Import the SQL file from the project folder

**Step 4 — Run the Project**
- Open browser and go to:
http://localhost/College-ERP-Management-System/index.php
---

## 🔐 Login Credentials (Demo)

| Role | Username | Password |
|------|----------|----------|
| Administrator | admin | admin123 |
| Faculty | faculty | faculty123 |
| Student | student | student123 |

---

## 📊 Database Tables

| Table | Description |
|-------|-------------|
| users | Stores login credentials and roles |
| students | Stores student personal details |
| faculty | Stores faculty details |
| results | Stores student marks and grades |
| subjects | Stores subject information |

---

## 🎯 Learning Outcomes

- Hands-on experience with PHP and MySQL web development
- Implemented role-based authentication and access control
- Understood database design and relational tables
- Applied SDLC process from planning to deployment
- Improved debugging and problem-solving skills

---

## 👩‍💻 Developer

**Ravikala**  
BCA Graduate — Bhandarkars Arts and Science College, Mangalore University 2026  
📧 ravikalashetty411@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/ravikalashetty0110)
