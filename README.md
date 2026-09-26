# Postgraduate-School-Of-Administration-Website-Application-Management-System
Full-stack postgraduate education website and application management platform with student portal, programme catalogue, application tracking, LMS and administrative management features.

# PSA Website & Application Management System

## Overview

The PSA Website & Application Management System is a modern,
database-driven education platform developed for the Postgraduate
School of Administration (PSA), formerly the Competency School of
Business Administration (COSBA).

The project combines an institutional website with an application
management and student administration platform, providing a centralized
digital environment for prospective students, enrolled students,
administrators and institutional management.

## Core Modules

### Public Website
- Home page
- About PSA
- Programmes
- Admissions
- Online application
- Application tracking
- Partner universities
- Scholarships
- Accreditations
- Events
- Blog
- Contact

### Student Portal
- Student registration
- Student login
- Application management
- Document submission
- Application tracking
- Programme information
- Learning Management System (LMS)
- Course access
- Student communications

### Application Management
- Online application forms
- Applicant records
- Application status tracking
- Document management
- Application workflow
- Tracking logs

### Administration Portal
- Student management
- Application management
- Programme management
- Scholarship management
- Partner university management
- Accreditation management
- Notices
- Content management
- Reports
- System settings
- SEO management

### Learning Management System
- Course management
- Course enrolment
- Student learning records
- LMS integration
- Digital learning support

## Technology Stack

### Frontend
- HTML5
- CSS3
- Bootstrap 5
- JavaScript
- jQuery
- Responsive Web Design

### Backend
- PHP
- PDO
- MySQL

### Database
The application uses a relational MySQL database to manage:

- Programmes
- Professional programmes
- Students
- Applications
- Documents
- Tracking logs
- LMS courses
- LMS enrolments
- Administrators
- Partners
- Notices
- System settings

## System Architecture

```text
                PSA WEBSITE
                     |
        +------------+------------+
        |                         |
        v                         v
  PUBLIC WEBSITE            STUDENT PORTAL
        |                         |
        |                  +------+------+
        |                  |             |
        v                  v             v
 Programmes          Applications      LMS
 Admissions          Documents         Courses
 Scholarships        Tracking          Enrolment
        |                  |
        +---------+--------+
                  |
                  v
            PHP APPLICATION
                  |
                  v
             MySQL DATABASE
                  |
                  v
            ADMIN PORTAL
                  |
      +-----------+-----------+
      |           |           |
      v           v           v
   Students   Applications  Programmes
      |
      +----------------------+
                             |
                             v
                  Reports / CMS / SEO
