# Employee Attendance Management System — Indian

Type: Full Stack

A professional full-stack employee attendance system for managing employees, daily attendance, leave, reports, and dashboards.

## Stack
Java 17 + Spring Boot + React + MySQL


## Setup
1. Create the MySQL database using `database/schema.sql`.
2. Configure MySQL username/password in `backend/src/main/resources/application.properties`.
3. Start the Spring Boot backend with `mvn spring-boot:run`.
4. Start React with `npm install` then `npm run dev`.


## Main Features
- Employee Management: add, view, edit, delete employees
- Department and designation management
- Daily check-in and check-out attendance
- Attendance status: Present, Absent, Late, Half Day, Leave
- Monthly attendance calendar and summary
- Leave request and approval workflow
- Search and filter employees
- Dashboard with employee count, present, absent, late and leave statistics
- Attendance reports with date/month filters
- Validation, error handling and responsive UI