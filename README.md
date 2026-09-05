# WebTech_PHP_Lab

A robust and feature-rich PHP-based web application developed as the Web Technologies final term lab project. This repository demonstrates core backend development principles, secure database operations, session management, and dynamic user interfaces built using native PHP and modern web standards.

---

## 🚀 Key Features

* **Secure Authentication System:** User registration, login, and logout functionalities with password hashing and session-based access control.
* **Complete CRUD Operations:** Full management capabilities allowing users to Create, Read, Update, and Delete records dynamically.
* **Database Integration:** Secure database connectivity using PHP Data Objects (PDO) / MySQLi with prepared statements to prevent SQL injection.
* **Form Validation & Security:** Robust server-side input sanitization and validation along with client-side error checking.
* **Responsive User Interface:** Clean, intuitive layout styled with modern CSS and utility frameworks for optimal viewing across devices.

---

## 🛠️ Tech Stack

* **Backend:** PHP (Native / Procedural & Object-Oriented)
* **Database:** MySQL
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
* **Server Environment:** Apache / Nginx (via XAMPP, WampServer, or Laragon)

---

## 📁 Project Structure

```text
WebTech_PHP_Lab/
│
├── assets/          # Stylesheets (CSS), client-side scripts (JS), and images
├── database/        # SQL schema dumps and database connection scripts
├── includes/        # Reusable layout templates (header, footer, navigation)
├── uploads/         # Directory for user-uploaded media and files
├── index.php        # Application entry point / dashboard
├── login.php        # User authentication portal
├── register.php     # New user registration interface
└── README.md        # Project documentation
```

---

## ⚙️ Getting Started & Installation

To run this project locally on your machine, follow these steps:

### Prerequisites
* A local server environment such as **XAMPP**, **WampServer**, or **Laragon** (ensuring PHP and MySQL are installed).
* **Git** installed on your system.

### Step 1: Clone the Repository
Open your terminal or command prompt and run:
```bash
git clone https://github.com/Rifat-009/WebTech_PHP_Lab.git
```

### Step 2: Move to Server Directory
Move the cloned project folder into your local server's root directory:
* For **XAMPP**: `C:\xampp\htdocs\WebTech_PHP_Lab`
* For **Laragon**: `C:\laragon\www\WebTech_PHP_Lab`

### Step 3: Set Up the Database
1. Start **Apache** and **MySQL** from your local server control panel.
2. Open your browser and navigate to **phpMyAdmin** (`http://localhost/phpmyadmin`).
3. Create a new database (e.g., `webtech_lab_db`).
4. Import the provided `.sql` database backup file located inside the `database/` folder of the project.

### Step 4: Configure Database Connection
Locate your database connection file (commonly found under `database/`, `config/`, or root directory) and update your database credentials if necessary:
```php
$host = 'localhost';
$username = 'root';
$password = '';
$dbname = 'webtech_lab_db';
```

### Step 5: Launch the Application
Open your web browser and access the project via:
```text
http://localhost/WebTech_PHP_Lab/
```

---

## 👤 Author

* **Arafatullah Rifat**
* Student, Computer Science and Engineering  
* American International University-Bangladesh (AIUB)
* Student ID : 23-54396-3
* GitHub: [@Rifat-009](https://github.com/Rifat-009)

---

## 📄 License

This project is developed for academic purposes as part of the Web Technologies course lab requirements.
