<p align="center">
  <img src="img/Automated-College-Timetable-Generator.jpg" alt="Automated College Timetable Generator Banner" width="100%" style="border-radius: 8px;" />
</p>

<h1 align="center">📅 Automatic Timetable Generator</h1>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-7.4%20%7C%208.x-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP Version" />
  <img src="https://img.shields.io/badge/MySQL-805A?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License" />
</p>

---

## 🌟 Overview

The **Automatic Timetable Generator** is a powerful, web-based solution built to optimize and automate the complex process of scheduling classes, lecturers, and classrooms. It helps educational institutions generate collision-free timetables dynamically, saving time and avoiding scheduling conflicts.

---

## 📸 Preview & Gallery

Here are some glimpses of the system interfaces:

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="img/Time-Table-Generator.jpg" alt="Timetable Layout" width="100%" style="border-radius: 6px;" /><br />
      <b>📈 Timetable Planner View</b>
    </td>
    <td align="center" width="50%">
      <img src="img/online-practice-exams.jpg" alt="Dashboard Panel" width="100%" style="border-radius: 6px;" /><br />
      <b>🖥️ Faculty & Exam Scheduling</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="img/exam-keys-show-examination-exams-or-test-online.jpg" alt="Exam Management" width="100%" style="border-radius: 6px;" /><br />
      <b>📋 Exam & Room Allocation</b>
    </td>
    <td align="center" width="50%">
      <img src="img/Blog-background-white-HNM-blue-gradient-blue-gear-faded.png" alt="System Settings" width="100%" style="border-radius: 6px;" /><br />
      <b>⚙️ Automated Scheduler Settings</b>
    </td>
  </tr>
</table>

---

## ⚡ Key Features

- **🛡️ Multi-Role Dashboards**:
  - **Admin**: Control and manage courses, semesters, subjects, classrooms, and teachers.
  - **Staff**: View assigned classes, schedules, and profile details.
  - **Student**: Effortlessly view and download semester-wise timetables.
- **⚡ Smart Collision Avoidance**: Prevents scheduling teachers or rooms in multiple slots at the same time.
- **🎨 Modern Design System**: Responsive grid built with Bootstrap and customized with a sleek glassmorphic theme.
- **🔄 Live AJAX Operations**: Dynamic dropdowns and real-time updates for selecting semesters and courses.

---

## 🛠️ Installation & Setup

Get the application running locally in just a few steps:

### 1. Clone & Set Up Project
Clone this repository to your local server directory (e.g. `htdocs` for XAMPP/WAMP):
```bash
git clone https://github.com/vijaymahes9080/timetable-php.git
```

### 2. Configure Database
- Open phpMyAdmin or your MySQL client.
- Create a new database named `timetable`.
- Import the SQL files from the [database/](file:///d:/BACKUP/projects/PHP%20project/timetable/database) directory.
- Update your database connection details in [config.php](file:///d:/BACKUP/projects/PHP%20project/timetable/config.php):
  ```php
  $conn = mysqli_connect("localhost", "your_username", "your_password", "timetable");
  ```

### 3. Open in Browser
Navigate to:
```
http://localhost/timetable/index.php
```

---

## 👥 Author

👤 **Vijay Mahes**
* Email: [Vijaypradhap2004@gmail.com](mailto:Vijaypradhap2004@gmail.com)
* GitHub: [@vijaymahes9080](https://github.com/vijaymahes9080)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
