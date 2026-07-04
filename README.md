<p align="center">
  <img src="img/header.jpg" alt="Automated College Timetable Generator Header" width="100%" style="border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);" />
</p>

<p align="center">
  <img src="img/customLogo.gif" alt="Timetable Generator Logo" width="80" style="vertical-align: middle; margin-right: 10px;" />
  <h1 align="center" style="display: inline-block;">📅 Automatic Timetable Generator</h1>
</p>

<p align="center">
  <a href="https://github.com/vijaymahes9080/timetable-php"><img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge" alt="Version" /></a>
  <img src="https://img.shields.io/badge/PHP-7.4%20%7C%208.x-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP Version" />
  <img src="https://img.shields.io/badge/MySQL-805A?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" alt="License" />
</p>

---

## 🌟 Introduction

Generating class schedules manually is time-consuming and prone to scheduling conflicts. The **Automatic Timetable Generator** is an intelligent web platform designed to automatically build optimal, collision-free timetables for educational institutions. It ensures that class hours, professors, subjects, and classrooms are aligned perfectly without overlaps.

---

## 📐 System Flow & Architecture

```mermaid
graph TD
    A[📅 Input: Courses, Subjects, Teachers & Rooms] --> B[⚙️ Core Scheduling Engine]
    B --> C{🛡️ Collision Check}
    C -- Collision Found --> D[🔄 Reschedule Slot]
    D --> B
    C -- Collision-Free --> E[💾 Save to Database]
    E --> F[🖥️ Admin Dashboard]
    E --> G[👩‍🏫 Staff Dashboard]
    E --> H[👨‍🎓 Student Dashboard]
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style C fill:#fdd,stroke:#333,stroke-width:2px
    style E fill:#bfb,stroke:#333,stroke-width:2px
```

---

## 📸 Interface Screenshots

### 🖥️ Dashboard & Scheduler Previews

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="img/Time-Table-Generator.jpg" alt="Timetable Layout" width="100%" style="border-radius: 6px;" /><br />
      <b>📈 Interactive Scheduler View</b>
    </td>
    <td align="center" width="50%">
      <img src="img/online-practice-exams.jpg" alt="Dashboard Panel" width="100%" style="border-radius: 6px;" /><br />
      <b>🖥️ Management Dashboard</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="img/exam-keys-show-examination-exams-or-test-online.jpg" alt="Exam Management" width="100%" style="border-radius: 6px;" /><br />
      <b>📋 Exam & Classroom Mapping</b>
    </td>
    <td align="center" width="50%">
      <img src="img/Blog-background-white-HNM-blue-gradient-blue-gear-faded.png" alt="System Settings" width="100%" style="border-radius: 6px;" /><br />
      <b>⚙️ Scheduler Settings & Configurations</b>
    </td>
  </tr>
</table>

### 📱 User & Module Previews

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="images/pic.jpg" alt="Login & Sign In Page" width="100%" style="border-radius: 6px;" /><br />
      <b>🔒 Secure Authentication Gateway</b>
    </td>
    <td align="center" width="50%">
      <img src="images/pic1.png" alt="Department & Course Setup" width="100%" style="border-radius: 6px;" /><br />
      <b>🏫 Departmental Configurations</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="images/pic2.jpg" alt="Staff Allocation" width="100%" style="border-radius: 6px;" /><br />
      <b>👩‍🏫 Lecturer & Faculty Allocations</b>
    </td>
    <td align="center" width="50%">
      <img src="images/pic3.jpeg" alt="Student Panel" width="100%" style="border-radius: 6px;" /><br />
      <b>🎓 Student Timetable Portal</b>
    </td>
  </tr>
</table>

---

## ⚡ Key Highlights

- **🤖 Automated Generation**: Computes optimal teacher-subject-slot combinations automatically.
- **🛡️ Collision Detection**: Built-in validation checks ensure no teacher or classroom is double-booked.
- **📊 Role-Based Control**:
  - **Admin**: Complete system overview (teachers, subjects, courses, slots).
  - **Staff**: Dedicated dashboard to check class schedules, profiles, and slots.
  - **Student**: Simple interface to view, export, or print semester-wise timetables.
- **⚡ Fast Web Architecture**: Utilizes AJAX dynamic queries for instant updates.

---

## 📂 Project Directory Structure

```text
timetable/
│
├── admin/            # Admin Panel templates, assets & scripts
├── staff/            # Staff Panel files and configuration
├── student/          # Student Portal views
├── database/         # Database SQL schemas
├── img/              # Primary site imagery and banners
├── images/           # UI screenshots and module illustrations
├── css/              # Shared Cascading Style Sheets
├── js/               # Shared JavaScript files
├── config.php        # Core Database Configurations
└── index.php         # Main landing page
```

---

## 🛠️ Installation & Setup

1. **Clone the Repo**:
   ```bash
   git clone https://github.com/vijaymahes9080/timetable-php.git
   ```
2. **Move to Web Directory**: Place the `timetable` directory in your local Apache `htdocs` or `www` folder.
3. **Database Import**:
   - Create a database in MySQL named `timetable`.
   - Import files located in the [database/](file:///d:/BACKUP/projects/PHP%20project/timetable/database) directory.
4. **Connect Database**:
   - Update database username, password, and hostname in [config.php](file:///d:/BACKUP/projects/PHP%20project/timetable/config.php).
5. **Access App**: Launch your web browser and open `http://localhost/timetable/`.

---

## 👥 Authorship & Contributions

👤 **Vijay Mahes**
* Email: [Vijaypradhap2004@gmail.com](mailto:Vijaypradhap2004@gmail.com)
* GitHub: [@vijaymahes9080](https://github.com/vijaymahes9080)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
