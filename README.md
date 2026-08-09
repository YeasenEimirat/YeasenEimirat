<h1 align="center">Hi 👋, I'm Yaseen Eimirat</h1>

<h3 align="center">Backend Developer Intern | C# & .NET</h3>

<p align="center">
Second-year Computer Systems Engineering student focused on backend development with C# and .NET.<br/>
I have a strong foundation in C#, C++, OOP, Data Structures, Algorithms, and SQL Server database design.<br/>
Currently developing and testing <b>PTC Hub</b>, a web platform designed for Palestine Technical College students.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Learning%20%26%20Building-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Focus-Backend%20Development-blue?style=for-the-badge" />
</p>

---

## 🎓 Education

| 🏫 Institution | 🎯 Degree | 📊 GPA |
|---|---|---|
| Palestine Technical College – Deir El Balah | B.Sc. Computer Systems Engineering — Second Year | **90.55%** |
| Shuhdaa Alnuseirat Secondary School | High School Diploma — 2023 | **97.60%** 🏅 Ranked 2nd in school |

---

## 🛠️ Technical Skills

**💻 Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**⚙️ Backend & .NET**

![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![ADO.NET](https://img.shields.io/badge/ADO.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=for-the-badge&logo=fastapi&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**🗄️ Database**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![ERD](https://img.shields.io/badge/Database_Design-ERD-1f6feb?style=for-the-badge)
![Normalization](https://img.shields.io/badge/Normalization-1f6feb?style=for-the-badge)

**🧠 Core Concepts**

![OOP](https://img.shields.io/badge/OOP-6e40c9?style=for-the-badge)
![Data Structures](https://img.shields.io/badge/Data_Structures-6e40c9?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Algorithms-6e40c9?style=for-the-badge)
![Problem Solving](https://img.shields.io/badge/Problem_Solving-6e40c9?style=for-the-badge)
![Three-Tier Architecture](https://img.shields.io/badge/Three--Tier_Architecture-6e40c9?style=for-the-badge)

**🧰 Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)
![SSMS](https://img.shields.io/badge/SSMS-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

---

## 🚀 Featured Projects

### ⭐ PTC Hub

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![ADO.NET](https://img.shields.io/badge/ADO.NET-512BD4?style=flat-square)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

> 🚧 **Project Status:** Under Development & Testing

PTC Hub is a web platform being developed for **Palestine Technical College students**. The project is currently in the **development and testing stage** and has not yet been released for student use.

#### 🔐 Authorization & Permission System

The system uses role- and year-based authorization:

| Role | Responsibilities |
|---|---|
| 🎓 **Student** | Accesses courses related to their academic year · Views general and year-specific announcements |
| 👨‍🏫 **Supervisor** | Responsible for a specific academic year · Manages content within their assigned year |
| 🛡️ **Admin** | Can be assigned to a specific academic year · General admins can manage system-wide operations |

> Authorization is enforced on the **server side**, not only through the frontend.

#### 📚 Course Management

- 📦 47 courses across 4 academic years
- 🗃️ Server-side course catalog
- ⭐ Course favorites
- 📅 Academic-year based course access

#### 📁 Course Files

- 🧑‍💼 Staff-uploaded files
- ✍️ Student file suggestions
- 🔄 Pending / approved / rejected workflow
- ✅ Supervisor-controlled approval
- 👁️ Year-based visibility

#### 📢 Announcements

- 🌍 General announcements
- 📌 Year-specific announcements
- 🔒 Server-side authorization and filtering

#### 📈 Progress Tracking

Students can track their progress for each course:

| Status | Meaning |
|---|---|
| ✅ `done` | Course completed |
| 🔄 `doing` | Course in progress |
| ⚪ `none` | Not started |

Also tracked: ⏱️ study hours · 📝 personal notes

#### 🔑 Password Management

- 🔁 Password change using the current password
- 🛠️ Admin password reset
- 📧 Forgot-password workflow
- 🔢 Email OTP verification
- ⏳ OTP expiration
- 🚫 Attempt limits

#### 👥 Student Management

- 🎯 Filter students by academic year
- 🔀 Move students between years
- 🎓 Year 5 represents graduated students

#### 🛡️ Security Safeguards

| Rule | Purpose |
|---|---|
| 🚫 No removing the last general admin | Ensures system always has an owner |
| 🔒 No self-privilege changes | Prevents users from editing their own role |
| ⛔ No self-promotion | Year supervisors can't promote themselves to general admin |
| 🖥️ Server-side authorization | Protects resources beyond the frontend |

#### ⚙️ Tech Stack

| Layer | Technology |
|---|---|
| 🧩 Backend | .NET 8 Web API |
| 🗄️ Database | SQL Server 2022 |
| 🔌 Data Access | ADO.NET |
| 🔑 Authentication | JWT Bearer |
| 🔐 Password Hashing | BCrypt |
| 📧 Email | Brevo REST API |
| ☁️ Hosting | Planned / Testing Stage |

🔗 **Repository:** [github.com/YeasenEimirat/PtcHub](https://github.com/YeasenEimirat/PtcHub)

---

### 🚗 Driving License Management System (DVLD)

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=.net&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows_Forms-0078D6?style=flat-square&logo=windows&logoColor=white)
![3-Tier](https://img.shields.io/badge/Architecture-3--Tier-6e40c9?style=flat-square)

A full desktop application simulating a real **Driving and Vehicle License Department**, built with C#, Windows Forms, SQL Server, and ADO.NET on a 3-Tier Architecture (Presentation, Business, Data Access layers).

#### 🏗️ Architecture

| Layer | Responsibility |
|---|---|
| 🖥️ Presentation | Windows Forms & User Controls — login, manage people/users, applications, tests, licensing screens |
| ⚙️ Business | Validations, business rules, and logic between UI and database |
| 🗄️ Data Access | SQL Server connectivity — insert, update, delete, search, stored procedures |

#### ✨ Main Features

| Module | Highlights |
|---|---|
| 👤 People Management | Add / update / delete, search by ID or National Number, prevent duplicates |
| 👥 Users & Login | Secure login, activate/deactivate accounts, password change, linked to a person record |
| 📋 Applications | New license, retake test, renewal, replacement, release detained, international license |
| 🧪 Test Management | Vision, Written, and Street tests — scheduling, results, retake handling |
| 📄 License Issuing | First-time issuing, license class, expiration date, fees |
| ♻️ Renewal & Replacement | Renew expired licenses, replace lost/damaged licenses, deactivate old license |
| 🚫 Detain / Release | Detain active licenses with fines, release after payment |
| 🌍 International License | Issue international license for valid local license holders, full history tracking |

#### 📜 Key Business Rules

- 🆔 A person can't be duplicated by National Number
- 🔗 Every user must be linked to an existing person
- 🚫 Inactive users can't log in
- 📶 Vision Test → Written Test → Street Test (strict order)
- 🔒 A detained license can't be renewed or replaced until released
- 🌍 International license requires a valid local license

**Concepts applied:** OOP · Reusable User Controls · Delegates & Events · Stored Procedures · 3-Tier Architecture

🔗 [View Project on GitHub](https://github.com/YeasenEimirat/-Driving-License-Management)

---

### 🏦 Bank Management System

![Java](https://img.shields.io/badge/Java-17%2B-orange?style=flat-square&logo=openjdk)
![JavaFX](https://img.shields.io/badge/JavaFX-21.0.2-blue?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-Project-C71A36?style=flat-square&logo=apachemaven)
![OOP](https://img.shields.io/badge/Design-Object--Oriented-success?style=flat-square)

> ✅ **Project Status:** Completed — team academic project

A complete academic banking application built in Java, demonstrating full OOP design with two interfaces (JavaFX GUI and Console) sharing the same business logic and text-file data storage.

| ✨ Feature |
|---|
| 🔐 Login system with input validation (max 3 attempts) |
| 🔒 Password encryption / decryption |
| 🛡️ User permissions (bitwise permission values) |
| 👤 Client management — add, edit, delete, search |
| 👥 User management — add, edit, delete, permission control |
| 💰 Banking transactions — deposit, withdraw, transfer |
| 📝 Transfer log & login register saved to text files |
| 💱 Currency management — search, update rates, convert |
| 📊 JavaFX dashboard with summary cards |
| 💾 File-based persistence in a `data` directory |

**OOP concepts demonstrated:** Classes & Objects · Encapsulation · Inheritance · Abstraction · Polymorphism · Composition · Enumeration

🔗 [View Project on GitHub](https://github.com/YeasenEimirat/Bank-Management-System)

---

## 🐍 GitHub Contributions

<p align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/YeasenEimirat/YeasenEimirat/output/github-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/YeasenEimirat/YeasenEimirat/output/github-snake.svg"
    />
    <img
      alt="GitHub Contribution Snake"
      src="https://raw.githubusercontent.com/YeasenEimirat/YeasenEimirat/output/github-snake.svg"
    />
  </picture>
</p>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=YeasenEimirat&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=YeasenEimirat&theme=github_dark" />
</p>

---

## 📫 Contact

<p align="center">
  <a href="https://github.com/YeasenEimirat"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:yaseeneimirat23@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

<p align="center">
  Thanks for visiting my profile! 🚀
</p>
