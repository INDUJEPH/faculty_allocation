The Smart Exam Resource Management System (SERMS) is an AI-powered solution designed to automate and optimize exam supervision, classroom allocation, and student distribution in universities and colleges. By leveraging AI-based scheduling, real-time validation, and an interactive dashboard, SERMS ensures efficient faculty assignment, fair student seating arrangements, and optimal resource utilization. With React (Vite) for UI and MySQL for data management, it provides a seamless experience for administrators, reducing manual workload while enhancing exam integrity and efficiency.


Table of Contents:

Overview

Key Features

Technologies Used


Overview:

SERMS is a comprehensive solution designed to eliminate manual errors in exam resource management by automating:
1. Faculty Supervision Allocation – Fairly assigns invigilators based on availability, workload, and seniority.
2. Exam Scheduling – Ensures no clashes for students with multiple subjects.
3. Classroom Management – Dynamically allocates rooms based on capacity and exam requirements.
4. Student Distribution – Splits students evenly across classrooms to avoid overcrowding.

Built with an interactive UI, real-time validation, and AI-driven scheduling, SERMS reduces administrative workload while ensuring transparency and efficiency.

 Key Features:
 
1️⃣ Faculty Supervision Management
Automated Assignment: AI assigns faculty based on availability, workload, and seniority.

Conflict Resolution: Detects and resolves scheduling clashes (e.g., same faculty in two exams).

Swap Suggestions: Recommends alternate faculty for duty exchanges.

2️⃣ Exam Scheduling
Multi-Subject Handling: Prevents exam clashes for students with core/elective subjects.

Real-Time Validation: Alerts if scheduling violates constraints (e.g., faculty unavailable).

3️⃣ Classroom Allocation
Dynamic Room Assignment: Matches exams with available classrooms based on capacity.

Seat Optimization: Ensures even distribution of students per room.

4️⃣ Student Management
Elective Handling: Smartly assigns students in elective courses without overlaps.

Personalized Schedules: Students can view their exam dates, times, and rooms.

5️⃣ Data Import/Export

Bulk Import: Upload faculty/student data, timetables, and room capacities via CSV/Excel.

Export Reports: Generate PDF/Excel files for seating plans, faculty duties, and exam schedules.

6️⃣ Admin & Coordinator Features
Admin Panel:

Manage faculty/student databases.

Set constraints (max workload, seniority rules).

Backup/restore system data.

Exam Coordinator Panel:

Adjust schedules manually via drag-and-drop UI.

Approve/reject supervision swaps.

7️⃣ Interactive Dashboard
Role-Based Views: Custom interfaces for Admins, Coordinators, and Students.

Drag-and-Drop Scheduling: Visually reschedule exams/faculty with real-time error checks.

Technologies Used:

Category	Technologies

Frontend: React.js

Backend: Node.js, Express.js

Database: MySQL (for structured data)

AI/Scheduling: Python (algorithm for conflict-free allocation)
