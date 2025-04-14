# 🎬 Movie Website

This Movie Website project was developed by **Nguyễn Thị Hoài Thương** and  **Ngô Thụy Thanh Tâm**.

- 🛠️ **Nguyễn Thị Hoài Thương** – Admin panel development
- 🧑‍💻 **Ngô Thụy Thanh Tâm** – Front-end and user interface design  

A dynamic web application built with **PHP**, **HTML**, **CSS**, **JavaScript**, and **MySQL** that allows users to browse, search, and filter movies, and provides admin functionalities for content management.

---
## ✨ Features

- List and display movie details
- User & admin login
- Search movies by title
- Filter by genre
- Admin panel for managing movies
- MySQL integration for storing user & movie data

---

## 📺 Demo

👉 [Movie Website Demo](https://www.youtube.com/watch?v=aYgYm7l4hq8)

---

## 🔧 Prerequisites

- Apache or Nginx web server
- PHP 7.4+
- MySQL
- Modern web browser

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AlbusRosie/Movie-Website.git
   cd Movie-Website
   
2. **Set Up the MySQL Database**
   - Import the `movie_website.sql` file located in the `database/` directory into your MySQL database.

3. **Update Database Configuration**
   - Open the `admin_page/assets/php/connect.php` and `user_page/connect.php` file and update the database credentials:
     ```bash
     $host = "localhost";
     $username = "your_username";
     $password = "your_password";
     $database = "your_database";
     ```

4. **Set Up the Web Server**
   - Place the project files in your web server's root directory (e.g., `htdocs/` for XAMPP).

5. **Run the Website**
   - Open your browser and navigate to:
     ```
     http://localhost/movie-website/<user_page/admin_page>/<filename.php>
     ```
---

## 📬 Contact

For feedback or questions, please reach out via GitHub or Gmail.

> ✨ *This project is for educational purposes only.*
