# Telehealth

**TeleHealth** is a full-stack web application designed to modernize healthcare access by connecting patients and doctors through secure video consultations, digital reports, and real-time dashboards. The platform ensures personalized healthcare experiences for both patients and providers.

---

## 📋 Table of Contents

- [Features](#features)
- [User Roles](#user-roles)
- [Tech Stack](#tech-stack)
- [Authentication](#authentication)
- [Getting Started](#getting-started)
- [Run the Project](#run-the-project)
- [App Navigation](#app-navigation)
- [Troubleshooting](#troubleshooting)
- [FAQs](#faqs)

---

## 🚀 Features

| Feature               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| Secure Authentication | JWT-based authentication with role-based access                             |
| Appointment System    | Book, reschedule, or cancel appointments                                    |
| Video Consultations   | Seamless Zoom integration for secure virtual meetings                       |
| Medical Reports       | Upload, store, and share digital medical documents                          |
| Health Dashboard      | Visualize metrics like heart rate, blood pressure, and more                 |
| Emergency Info Card   | One-click emergency medical information access                              |
| Responsive UI         | Accessible on desktop, tablet, and mobile                                   |

---

## 👥 User Roles

### 🧑‍⚕️ Doctors
- Register and manage profiles
- Set consultation availability
- Join video appointments
- View and update patient reports

### 🧑 Patients
- Register and manage health profiles
- Book, join, and cancel appointments
- View health metrics and upload reports
- Access emergency medical details

### 🛠️ Admin
- Manage user accounts
- Oversee platform performance and usage
- Handle support requests
- Configure system-level settings

---

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose)
- **Authentication**: JWT (JSON Web Tokens)
- **Video Integration**: Zoom API
- **State Management**: Redux Toolkit (if used)

---

## 🔐 Authentication & Hashing

- **Password Hashing**: All user passwords are hashed using `bcrypt` before storage.
- **JWT Tokens**: Authenticated sessions use JWTs to manage and verify user sessions.
- **Role-based Access**: Pages and routes are protected based on user type (Doctor, Patient, Admin).

---
