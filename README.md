# Complete-IAA-House-Points

**Housepoints management software** used in the International Academy Amman — the #1 ranked International Baccalaureate school in Jordan.

![HousePointMain](https://private-user-images.githubusercontent.com/76060515/345389239-d11048b0-c4ae-4bc8-9cdd-a8ad98bc808f.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU5MjIzNDYsIm5iZiI6MTc0NTkyMjA0NiwicGF0aCI6Ii83NjA2MDUxNS8zNDUzODkyMzktZDExMDQ4YjAtYzRhZS00YmM4LTljZGQtYThhZDk4YmM4MDhmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA0MjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNDI5VDEwMjA0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTUwYmE3NjMyNTRmYzdjNzA5MWJkMjEyOTg0NWZmMjRmMDEwYzc2MDI3YTJhNjY2MzBmZmNiMDgzNzNmYTAwOWImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.0NQJxrTCNIJrSCtpUtmIwU7-wr2NZsHMEwtb8YB6oBU)
---

## 👥 Team Members
- **Hashem** (me) — Backend, Database, Server  
- **Amin** — Frontend, Backend, Server  
- **Yamin** — Frontend, Database  
- **Mohe** — Frontend

---

## 📌 Project Overview

The Housepoints project was developed by a team of four students to create a relational database and web application that enables administrators to:

- Manage individual student house points.
- Track house-wide point totals.
- Search points by house or student.
- View leaderboards based on the **IB learning profiles**.

---

## ✨ Key Features

- **Admin Management**: Admins can manage house points for both students and houses.
- **User Search**: Users can search for points by house and student.
- **Leaderboards**: View leaderboards specialized to the IB learner profiles.

---

## 🛠 Technology Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: PHP  
- **Database**: MySQL (managed via phpMyAdmin)  
- **Server**: XAMPP for local development

---

## 🧩 Installation Instructions

### 1. Download and Install XAMPP
- Go to the [XAMPP website](https://www.apachefriends.org/index.html) and download the installer for your OS.
- Follow the installation instructions provided on the site.

### 2. Download the Project
- Download the ZIP file from this GitHub repository.
- Extract it into your `htdocs` directory (usually `C:\xampp\htdocs` on Windows or `/Applications/XAMPP/htdocs` on macOS).

### 3. Set Up the Database
- Open [phpMyAdmin](http://localhost/phpmyadmin) in your browser.
- Create a new database (name it anything you like).
- Import the provided `.sql` file (found in the project folder) to create tables and sample data.

### 4. Run the Project
- Open your browser and go to:  
  `http://localhost/your_project_folder/index.php`  
- This will launch the web app where you can begin using the Housepoints system.

---

## 🚀 Usage

- **Admin Panel**: Log in as an admin to manage house points.
- **Search**: Look up points by house or student name.
- **Leaderboards**: View and filter leaderboards according to IB learner profiles.

---

## 🖼 Screenshots from Application

![Screenshot 1](https://private-user-images.githubusercontent.com/76060515/345389341-adffb1a0-aeda-4837-a673-48165bdade4c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU5MjIzNDYsIm5iZiI6MTc0NTkyMjA0NiwicGF0aCI6Ii83NjA2MDUxNS8zNDUzODkzNDEtYWRmZmIxYTAtYWVkYS00ODM3LWE2NzMtNDgxNjViZGFkZTRjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA0MjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNDI5VDEwMjA0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWM4M2QwMTdjNTQyNzU0NzY2ZjdjM2QxZjFhNDEyYjQ5NDcyZmE3MzFjYTU1YjkxOTk1NzRiYWU0NjQ3MDc3ODMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.asRHkHy90HLlY4F2wYD9a2PGt14C2jTPNlQmGZDpTCk)  
![Screenshot 2](https://private-user-images.githubusercontent.com/76060515/345389387-fa1bda62-19bd-4345-bd70-0c2fcaad2178.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU5MjIzNDYsIm5iZiI6MTc0NTkyMjA0NiwicGF0aCI6Ii83NjA2MDUxNS8zNDUzODkzODctZmExYmRhNjItMTliZC00MzQ1LWJkNzAtMGMyZmNhYWQyMTc4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA0MjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNDI5VDEwMjA0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTMyN2M2MzdiNzkzMTA1ZTI5ZjZhZjc2NzkzZWViNGU1NmZkYWQyOTA5NDVkMjRjZGJlNjNiOGM4NmYwYjAzYWUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.3XBNPgeoorJLMRpSmFKK-YAZNkJ3ErvWKvSVSLL-0oo)  
![Screenshot 3](https://private-user-images.githubusercontent.com/76060515/345389534-6c969e3f-4053-417a-9344-c77a1aa8f2bc.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU5MjIzNDYsIm5iZiI6MTc0NTkyMjA0NiwicGF0aCI6Ii83NjA2MDUxNS8zNDUzODk1MzQtNmM5NjllM2YtNDA1My00MTdhLTkzNDQtYzc3YTFhYThmMmJjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA0MjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNDI5VDEwMjA0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWRiYzkyNTQxM2M3ODEyMWM0OTA4ZTc3OTg1NDhmYWViM2IxZTk0OTg2YmIwNGU0ZGUzMzFlNjY3NzU2NDVlNGYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.heOvGW09lTfgm8_owavpV1emxISnwq_wJWzfwNBsIeI)  
![Screenshot 4](https://private-user-images.githubusercontent.com/76060515/345389447-3b0ce08c-06a7-4861-82f6-5c3806b48b84.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDU5MjIzNDYsIm5iZiI6MTc0NTkyMjA0NiwicGF0aCI6Ii83NjA2MDUxNS8zNDUzODk0NDctM2IwY2UwOGMtMDZhNy00ODYxLTgyZjYtNWMzODA2YjQ4Yjg0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA0MjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwNDI5VDEwMjA0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWVjMDg1YWJiMWQ4OThhNjQ3OTIyODA2YTcwN2FiOGZhNzk3OTVjOTBjNzA3NzI2ZmQyMzA1YTU4NGM4ZGRmMzYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.aGgX1PQDzmqRLh9J67Hm5q9BfU6KrLfPe-4jXa5Ddw4)

---

## 🤝 Contribution

Feel free to **fork** this project, **submit pull requests**, and **report any issues**. Contributions are welcome and appreciated!

---

## 🙏 Acknowledgments

Thanks to our team members for their hard work and collaboration, and to our mentors and teachers for their valuable guidance and support.
