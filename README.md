
# Student Management System

## Project Overview
The Student Management System is a web-based application developed using Python and Flask. It helps manage student information, record attendance, maintain academic results, and view important statistics through an interactive dashboard.

## Objectives
- Manage student records efficiently.
- Add, view, edit, and delete student information.
- Record and manage daily attendance.
- Store subject-wise marks and calculate grades.
- Display student and academic statistics using charts.
- Store application data in an SQLite database.

## Technologies Used
- Python 3.13
- Flask
- SQLite
- HTML
- CSS
- JavaScript
- Chart.js
- Visual Studio Code

## Main Features

### 1. Dashboard
- Total number of students.
- Attendance statistics.
- Present and absent counts.
- Total result records.
- Average marks.
- Charts for course-wise students, attendance, and subject-wise marks.

### 2. Student Management
- Add new students.
- View student records.
- Search students.
- Edit student details.
- Delete student records.

### 3. Attendance Management
- Mark students as Present or Absent.
- Record attendance by date.
- View attendance records.
- Delete attendance records.

### 4. Results Management
- Enter subject-wise marks.
- Calculate grades automatically.
- View result summaries.
- Edit and delete marks.

## Project Structure

```text
student_attendance_system/
│
├── app.py
├── database.py
├── requirements.txt
├── README.md
│
├── database/
│   └── students.db
│
├── templates/
│   ├── index.html
│   ├── add_student.html
│   ├── view_students.html
│   ├── edit_student.html
│   ├── attendance.html
│   ├── results.html
│   └── edit_result.html
│
└── static/
    └── css/
        └── style.css
```

## Installation and Setup

### Step 1: Install Python
Install Python 3.13 or a compatible Python 3 version.

### Step 2: Download the Project
Clone the repository or download the project files.

### Step 3: Open the Project Folder
Open the project folder in Visual Studio Code.

### Step 4: Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 5: Initialize the Database

```bash
python database.py
```

### Step 6: Run the Application

```bash
python app.py
```

### Step 7: Open in Browser

Visit:

http://127.0.0.1:5000

## Database
The application uses SQLite to store student information, attendance records, and academic results. The database tables are created automatically when the application starts.

## Python Concepts Used
- Functions and modules
- Conditional statements and loops
- Lists and dictionaries
- Database connectivity
- SQL queries and CRUD operations
- Exception handling and input validation
- Flask routing
- HTML templates and form handling

## Future Enhancements
- Student login and authentication.
- Export student reports to PDF or Excel.
- Attendance percentage reports.
- Advanced search and filtering.

## Project Conclusion
The Student Management System provides a simple and organized way to manage student details, attendance, and academic results. It demonstrates the practical use of Python, Flask, SQLite, and web technologies in developing an integrated application.
