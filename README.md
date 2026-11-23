# Online Examination System

## 📌 Project Description
The Online Examination System is a web-based application developed using Python Flask, HTML, CSS, and JavaScript. It provides a digital platform for conducting examinations online. Students can attend multiple-choice examinations, submit their answers, and view their results automatically.

## 🎯 Problem Statement
Traditional examination systems involve manual question paper preparation, answer evaluation, and result processing. These processes consume time and may lead to errors. The Online Examination System aims to simplify the examination process by providing an automated platform for conducting examinations, evaluating answers, and generating results.

## 🎯 Objectives
- To conduct examinations through an online platform.
- To reduce manual examination and evaluation work.
- To provide automatic mark calculation.
- To provide a user-friendly interface for students.
- To allow administrators to manage examination questions and view results.

## ✨ Features

### Student Module
- Student login
- Student dashboard
- View available examinations
- Attend multiple-choice questions (MCQs)
- Countdown examination timer
- Automatic submission when time expires
- View examination results

### Admin Module
- Admin login
- Admin dashboard
- Add examination questions
- Manage question bank
- View student examination results

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| HTML | Structure of web pages |
| CSS | Styling and design |
| JavaScript | Timer and interactive features |
| In-memory storage | Sample data management |

## 📂 Project Structure

```text
Online-Examination-System/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   ├── base.html
│   ├── login.html
│   ├── student_dashboard.html
│   ├── admin_dashboard.html
│   ├── exam.html
│   ├── result.html
│   └── 404.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── timer.js
│
└── diagrams/
    ├── use_case.puml
    ├── class_diagram.puml
    ├── activity_diagram.puml
    ├── sequence_diagram.puml
    └── deployment_diagram.puml
```

## ⚙️ Installation and Execution

**Step 1:** Clone the repository.

```bash
git clone https://github.com/YOUR-USERNAME/Online-Examination-System.git
```

**Step 2:** Open the project folder.

```bash
cd Online-Examination-System
```

**Step 3:** Create a virtual environment.

```bash
py -m venv venv
```

**Step 4:** Activate the virtual environment.

```bash
venv\Scripts\activate
```

**Step 5:** Install the required packages.

```bash
pip install -r requirements.txt
```

**Step 6:** Run the application.

```bash
python app.py
```

**Step 7:** Open the application in your browser.

```text
http://127.0.0.1:5000
```

## 🔑 Demo Login Credentials

| User Role | Username | Password |
|---|---|---|
| Student | student | student123 |
| Admin | admin | admin123 |

## 📊 UML Diagrams

The project includes the following UML diagrams:

1. Use Case Diagram
2. Class Diagram
3. Activity Diagram
4. Sequence Diagram
5. Deployment Architecture Diagram

## 🚀 Future Enhancements
- Database integration using MySQL.
- Student registration functionality.
- Secure password encryption.
- Random question generation.
- Downloadable examination reports.
- Advanced examination monitoring.

## 📝 Conclusion
The Online Examination System provides an efficient and user-friendly platform for conducting examinations digitally. It reduces manual work, automates answer evaluation, and helps students receive their results quickly.

---

**Project Title:** Online Examination System

**Technology:** Python Flask, HTML, CSS and JavaScript

**Project Type:** Web-Based Application

**Storage:** In-memory sample data
