# Full Stack User Management System - Vector Vault

## Project Overview
This is a full-stack PHP web application featuring user registration, secure login, a personalized dashboard, and an administrative user registry.

## Technologies Used
* **Frontend:** Tailwind CSS & Custom Glassmorphism CSS
* **Backend:** PHP (PDO)
* **Database:** MariaDB / MySQL

## Setup Instructions
1. **Database Import:**
   - Open phpMyAdmin.
   - Create a new database named `user_system`.
   - Import the provided `user_system.sql` file.
2. **Local Hosting:**
   - Place all files in your XAMPP `htdocs` folder.
   - Ensure Apache and MySQL are running in the XAMPP Control Panel.
3. **Access:**
   - Open `http://localhost/[Your_Folder_Name]/index.php` in your browser.

## Features
* Secure password hashing using `password_hash()`.
* Session-based authentication.
* Responsive design using Tailwind CSS.
* Complete User Registry table for administrative viewing.