# Clash-Free University Timetable Generator

An AI-powered clash-free timetable generator designed for universities and educational institutions.  
The system automatically generates optimized class schedules while avoiding timetable conflicts between teachers, rooms, students, and subjects.

---

# Features

- Automatic clash-free timetable generation
- Teacher availability management
- Classroom allocation system
- Department-wise scheduling
- Semester and section management
- Subject credit-hour handling
- Constraint-based scheduling algorithm
- AI/Optimization-based timetable generation
- Export timetable as PDF/Excel
- Admin dashboard
- Student & Faculty timetable views
- Real-time conflict detection
- Responsive web interface

---

# Problem Statement

Manual timetable generation in universities is time-consuming, error-prone, and difficult to manage when handling multiple departments, teachers, rooms, and semesters.  
This project automates the scheduling process using intelligent algorithms to generate optimized and clash-free timetables efficiently.

---

# Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Axios

## Backend
- Node.js
- Express.js

## Database
- MongoDB

## AI / Optimization
- Genetic Algorithm / Constraint Satisfaction Algorithm

## Authentication
- JWT Authentication

## Deployment
- Vercel / Netlify (Frontend)
- Render / Railway / AWS (Backend)

---

# System Modules

## Admin Module
- Manage departments
- Manage teachers
- Add classrooms
- Add semesters & sections
- Configure timetable constraints
- Generate timetables

## Teacher Module
- View assigned schedule
- Manage availability
- Receive updates

## Student Module
- View class timetable
- Department-wise filtering

---

# Constraints Handled

The system ensures:

- No teacher clash
- No classroom clash
- No section overlap
- Proper credit-hour distribution
- Break timing support
- Lab scheduling support
- Teacher workload balancing

---

# Project Architecture

``` id="yzmya6"
Frontend (React)
       ↓
Backend API (Node.js + Express)
       ↓
Scheduling Engine (AI Algorithm)
       ↓
MongoDB Database
