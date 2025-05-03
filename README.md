# Academic Portal Web Application

## Overview

This project is a full-stack web application designed to streamline academic activities between faculty, students, and academic administrators. It serves as a centralized academic portal where:

- **Faculty** can float courses, manage enrollments, and assign grades.
- **Students** can browse available courses and apply for enrollment.
- **Academic Staff** can monitor course activities and access grading information efficiently.

The portal aims to reduce administrative overhead and enhance user experience for all academic stakeholders.

## Features

- **Faculty Dashboard**:
  - Float and manage multiple courses.
  - View student applications.
  - Select or remove students from a course.
  - Assign grades to enrolled students.

- **Student Dashboard**:
  - Browse and enroll in floated courses.
  - Track application status and grades.

- **Academic Staff Access**:
  - View course participation and performance data.
  - Oversee grading and enrollment workflows.

## Technologies Used

- **Frontend**: ReactJS, HTML, CSS, Bootstrap/Tailwind (update as per your setup)
- **Backend**: NodeJS, ExpressJS
- **Database**: MongoDB (or any DB used)
- **Authentication**: JWT, bcrypt
- **Others**: REST APIs, dotenv for environment variables, CORS handling

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/academic-portal.git
   cd academic-portal
2. **Create the Virtual Environment
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   
3. **Install the dependencies
   ```bash
   pip install flask flask_sqlalchemy flask_mail flask_migrate psycopg2

4. replace postgresql://ashutosh:12345@localhost:5432/mydatabase with your own postgresql database






