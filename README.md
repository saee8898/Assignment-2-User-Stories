# Assignment-2-User-Stories
# Student Attendance Management System

## 1. Project Introduction

The Student Attendance Management System is a web-based application designed to manage student attendance records efficiently.

It helps teachers mark attendance, students view their attendance details, and administrators manage student records.

## 2. Project Objectives

- To maintain student attendance records.
- To reduce manual attendance work.
- To provide accurate attendance reports.
- To help students track their attendance percentage.

## 3. Main Features

- User Login
- Student Management
- Teacher Management
- Mark Attendance
- View Attendance
- Generate Attendance Reports

## 4. Stakeholder Identification

| Stakeholder | Role and Responsibility |
|---|---|
| Student | View personal attendance records |
| Teacher | Mark and update attendance |
| Admin | Manage students and teachers |
| Principal | Monitor overall attendance reports |
| HOD | Monitor department-wise attendance |

## 5. User Stories

### US01 – Student Login
As a student, I want to login, so that I can access my attendance details.

### US02 – View Attendance
As a student, I want to view my attendance, so that I can track my presence.

### US03 – Attendance Percentage
As a student, I want to view my attendance percentage, so that I can know my attendance status.

### US04 – Teacher Login
As a teacher, I want to login, so that I can manage attendance.

### US05 – Mark Attendance
As a teacher, I want to mark attendance, so that student attendance records are maintained.

### US06 – Update Attendance
As a teacher, I want to update attendance, so that incorrect records can be corrected.

### US07 – Add Students
As an admin, I want to add students, so that their records are maintained in the system.

### US08 – Generate Reports
As a principal, I want to generate attendance reports, so that I can monitor student attendance.



## 6. Acceptance Criteria

### AC01 – Student Login
- Given: Student has a registered account.
- When: Student enters valid username and password.
- Then: System should allow the student to login.

### AC02 – View Attendance
- Given: Student is logged into the system.
- When: Student clicks on View Attendance.
- Then: System should display attendance records.

### AC03 – Attendance Percentage
- Given: Student attendance records are available.
- When: Student opens the attendance percentage section.
- Then: System should display the correct attendance percentage.

### AC04 – Teacher Login
- Given: Teacher has a registered account.
- When: Teacher enters valid login credentials.
- Then: System should open the teacher dashboard.

### AC05 – Mark Attendance
- Given: Teacher is logged in and has selected a class and date.
- When: Teacher marks students as Present or Absent and submits.
- Then: System should save the attendance records.

### AC06 – Update Attendance
- Given: An attendance record already exists.
- When: Authorized teacher updates the attendance status.
- Then: System should save the updated status.

### AC07 – Add Students
- Given: Admin is logged into the system.
- When: Admin enters valid student details and clicks Save.
- Then: System should add the student record.

### AC08 – Generate Reports
- Given: Attendance records are available.
- When: Principal selects a date range and requests a report.
- Then: System should generate the attendance report.
-
