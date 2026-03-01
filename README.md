# login-php-backend-connection
login web page with back end  php authentication system
# 🔐 PHP Authentication System

A secure and scalable user authentication system built using PHP and MySQL.  
This project demonstrates backend development skills including session management, database connectivity, and user validation.

---

## 📌 Project Overview

This application provides a complete Login and Registration workflow with secure password handling and database-driven authentication.

The system validates user credentials, prevents duplicate registrations, and restricts unauthorized access using PHP sessions.

---

## 🚀 Features

- User Registration with validation
- Secure Login Authentication
- Password Encryption (MD5)
- Session Management
- Duplicate Email Detection
- MySQL Database Integration
- Error Handling & Redirection

---

## 🛠️ Tech Stack

- PHP (Core Backend Logic)
- MySQL (Database)
- HTML5
- CSS3
- XAMPP (Local Development Environment)

---

## 🗄️ Database Structure

**Table: users**

| Field      | Type        |
|------------|------------|
| id         | INT (Auto Increment) |
| firstName  | VARCHAR |
| lastName   | VARCHAR |
| email      | VARCHAR |
| password   | VARCHAR |

---

## ⚙️ Installation Guide

1. Clone the repository
2. Import the SQL file into phpMyAdmin
3. Update database credentials in `connect.php`
4. Run the project on localhost

---

## 📈 Future Improvements

- Use bcrypt instead of MD5
- Add email verification
- Add password reset feature
- Implement prepared statements for better security
- Add dashboard UI improvements


**Anil Kumar**

Aspiring Full Stack Developer passionate about backend systems and secure authentication workflows.
