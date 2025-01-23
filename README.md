# College Management System

This is a web-based College Management System designed to streamline and automate various administrative and academic processes within a college. It leverages modern web technologies to provide an efficient and user-friendly platform for managing college operations.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [Installation](#installation)

## Features

The College Management System offers the following features:

- **Student Management**: Manage student information, including personal details, enrollment, and academic records.
- **Faculty Management**: Handle faculty details, assignments, and schedules.
- **Course Management**: Organize courses, syllabi, and associated resources.
- **Attendance Tracking**: Monitor and record student attendance efficiently.
- **Grading System**: Facilitate grade entry, calculation, and report generation.
- **Library Management**: Oversee library resources, lending, and returns.
- **Timetable Scheduling**: Create and manage class and exam timetables.
- **User Authentication**: Secure login for administrators, faculty, and students.

## Technologies Used

The system is built using the following technologies:

- **Frontend**:
  - AngularJS: For dynamic and responsive user interfaces.
  - HTML5 & CSS3: For structuring and styling web pages.
  - Bootstrap: For responsive design and layout.
- **Backend**:
  - ASP.NET MVC 5: For server-side logic and handling HTTP requests.
  - Entity Framework 6: For object-relational mapping and database interactions.
- **Database**:
  - LocalDB: A lightweight version of SQL Server for data storage.

## System Architecture

The project follows a layered architecture to promote separation of concerns and enhance maintainability:

1. **Data Layer**:
   - **CMS.Data**: Contains business entities representing the core data structures.
   - **CMS.Repository**: Provides data access abstraction and repository patterns.
2. **Service Layer**:
   - **CMS.Services**: Implements business logic and interacts with the data layer.
   - **CMS.Configuration**: Manages configuration settings and messaging.
3. **Presentation Layer**:
   - **CMS.UI**: Handles user interactions, input validation, and displays information using AngularJS and ASP.NET MVC.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/niyathnair/CMS-Application-dotNET.git
## Collaborators

Niyath Nair, Chaital Ghan
