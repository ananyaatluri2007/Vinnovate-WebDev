University Management System 
A centralized backend engine for a university management portal, providing specialized interfaces and data access for students, faculty, and parents. The system is designed to bridge the communication gap between the institution and home while managing core academic operations.

User Roles & Access
Students: Course registration, attendance tracking, and digital assignment submissions.

Faculty: Grade entry, attendance management, and student performance monitoring.

Parents: Real-time access to ward performance, attendance alerts, and fee payment history.
Role-Based Access: Distinct authentication layers for Students, Faculty, and Administrators.

Academic Records: Secure endpoints for handling digital assignments, exam schedules, and marks entry.

Project Structure
src/api — Role-specific endpoints for Student, Faculty, and Parent portals.

src/services — Logic for registration, attendance calculation, and reporting.

src/models — Relational schema for linking Students to Parents and Faculty to Courses.

src/auth — Multi-layered authentication and permission guards.


Tech Stack
Language/Runtime: [Node.js]
Database: [MongoDB] — optimized for relational academic data.
POSTMAN for testing

Auth: [JWT-based] secure session management.

Project Structure
/routes - API endpoints for students and faculty.

/models - Schema definitions for Users, Courses, and Grades.

/middleware - Auth guards and input validation.
