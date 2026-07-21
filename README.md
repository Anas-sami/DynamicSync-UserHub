# DynamicSync-UserHub
A dynamic user management web application built with PHP, MySQL, HTML, CSS, and JavaScript, featuring real-time status updates via AJAX. Developed as part of the Web Development Training at Smart Methods.


# Dynamic User Management & Status Toggle System

This project is a practical task developed as part of the **Web Development Track** at **Smart Methods**. It is a lightweight web application designed to demonstrate frontend-backend integration, data persistence, and asynchronous updates using native web technologies, PHP, and MySQL.

## 🔗 Live Demo
You can view the live running project here: [http://anas.howto.rocks](http://anas.howto.rocks)

---

## 📂 Project Structure & Files
The repository contains the following core files:
1. **`db.php`**: Manages the secure connection to the MySQL database using PHP PDO.
2. **`index.php`**: Handles the frontend UI (HTML/CSS), processes form submissions, queries the database, and implements JavaScript (Fetch API) for real-time interactions.

---

## ✨ Key Features & Implementation Steps

1. **Frontend & Form Design:** * Built using clean HTML and CSS.
   * Features a simple input form with fields for **Name** and **Age**, alongside a **Submit** button and a live data display table.

2. **Database Storage (MySQL):** * Submitted user data is processed via PHP and securely stored in a MySQL table named `users` (tracking `id`, `name`, `age`, and `status`).

3. **Live Data Display:** * All records saved in the database are dynamically fetched and presented in a structured table right beneath the input form.

4. **Status Toggle & Real-time Updates (AJAX / JavaScript):** * Every record includes a dynamic **Toggle** button.
   * Clicking the button triggers an asynchronous request via JavaScript (`Fetch API`) to update the status value in the database (`0` to `1` or vice versa) and instantly refreshes the UI **without requiring a page reload**.

---

## 🚀 How to Setup
1. Upload `db.php` and `index.php` to your web server or hosting provider (e.g., InfinityFree).
2. Create a MySQL table named `users` with the columns: `id` (Primary Key, Auto Increment), `name` (VARCHAR), `age` (INT), and `status` (INT, default 0).
3. Update your database credentials inside `db.php`.
4. Open your domain in the browser to start using the application!

---

## 👨‍💻 Author
**Anas Sami Al-Harthi** Smart Methods Training Program 2026
