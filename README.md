# POPP - Student Attendance Management App

 **Project Context:** Eco-designed mobile application to manage student attendance at ENSISA.
 
 **Format:** Team Project (7 Students) | Engineering School

## Project Overview
**POPP** ("Présent ou Pas Présent") is a cross-platform mobile application designed to digitize and simplify attendance tracking.
The app provides specific interfaces for 4 types of users: **Students, Teachers, School Administration, and Admins**.

Key focus was placed on **Eco-design** to reduce battery and data consumption.

## Tech Stack
* **Framework:** Flutter (Dart) - Cross-platform (Android/iOS).
* **Database:** SQLite (Local storage) & SFTP for secure data transfer.
* **Hardware:** Data hosted locally on a **Raspberry Pi** for security.
* **Tools:** Android Studio.

## Key Features by Role

### Student
* **Schedule:** View upcoming classes and room details.
* **Attendance Tracking:** Real-time stats on personal presence/absence rates.

### Teacher
* **Session Management:** Create sessions and scan/mark attendance.
* **One-Click Validation:** Mark students as Present, Late, or Absent quickly.
* **Statistics:** View attendance rates per course or per specific student.

### School Administration & Admin
* **User Management:** Create student/teacher accounts and assign roles.
* **Schedule Management:** Edit global timetables.
* **Technical Monitoring:** Database integrity checks and debugging.

## Eco-Design & Performance
We implemented specific strategies to minimize the app's carbon footprint:
* **Dark Mode:** Native support to save energy on OLED screens.
* **Optimized Requests:** Fetching only strictly necessary data.
* **Minimalist UI:** Using system fonts and limiting heavy animations.

