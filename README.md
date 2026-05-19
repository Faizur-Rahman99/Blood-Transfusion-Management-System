# Blood Transfusion Management System

## Overview

The **Blood Transfusion Management System** is a Java desktop application designed to streamline and digitize blood donation and transfusion operations.

The system helps hospitals or blood centers manage:

- Blood donor records
- Patient registrations
- Blood inventory
- Donation history
- Blood reservations
- Appointments
- Plasma and platelet donor data

The goal is to improve efficiency, reduce manual errors, and ensure faster access to compatible blood for patients.

---

## Features

### Donor Management
- Add new blood donors
- Update donor details
- Delete donor records
- Search donors by:
  - Blood group
  - Location

---

### Patient Management
- Register patients
- Store patient details
- Track transfusion requests

---

### Blood Inventory Management
- Track available blood stock
- View blood details
- Automatically decrease stock after transfusion

---

### Reservation System
- Add blood reservations
- View reservation details
- Manage blood allocation

---

### Appointment Management
- Schedule appointments
- View appointment records

---

### Donation Tracking
- Store donation records
- View donor donation history

---

### Specialized Donor Categories
- Plasma donor management
- Platelet donor management

---

### Authentication
- Login system for authorized access

---

## Technology Stack

### Programming Language
- Java

### GUI Framework
- Java Swing

### IDE
- NetBeans

### Database
- MySQL

### Build Tool
- Apache Ant

---

## Database Setup

This project includes the SQL database file:

```text
Blood_Sql.sql
```

### To set up the database:

1. Open MySQL or phpMyAdmin
2. Create a new database
3. Import:

```text
Blood_Sql.sql
```

---

## How to Run

### Option 1: Using NetBeans
1. Open NetBeans
2. Open the project folder
3. Build the project
4. Run the application

---

### Option 2: Using Command Line
```bash
ant build
ant run
```

---

## Project Structure

```text
src/            → Java source files
build/          → Compiled files (ignored in Git)
nbproject/      → NetBeans project settings
Blood_Sql.sql   → Database schema
build.xml       → Ant build configuration
```

---

## Project Goal

To provide a complete digital solution for blood transfusion and donor management that improves accessibility, organization, and operational efficiency in healthcare settings.

---

## License

This project is for academic and educational purposes.
