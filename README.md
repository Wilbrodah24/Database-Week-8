# 🏥 Clinic Booking System Database

## 📌 Project Description

The **Clinic Booking System Database** is a full-featured MySQL-based relational database designed to manage core operations of a healthcare clinic. It includes robust support for users, roles, patients, doctors, appointments, prescriptions, payments, tests, and rooms.

This project is built with **pure SQL**, using proper relational principles—primary and foreign keys, normalization, and constraints—to ensure data integrity and scalability.

---

## ⚙️ Features

- ✅ User authentication system with roles (Admin, Doctor, Receptionist)
- ✅ Department and doctor management
- ✅ Room allocation for appointments
- ✅ Patient registration and appointment booking
- ✅ Prescription issuance and medication management
- ✅ Medical test management and results logging
- ✅ Payment tracking for appointments
- ✅ 1-to-1, 1-to-many, and many-to-many relationships handled effectively

---

## 📁 File Structure

clinic-booking-db/
├── clinic_booking_system.sql
├── README.md
└── assets/
    └── ERD.png

---

## 🛠️ Setup Instructions

### 📦 Requirements

- MySQL Server (v5.7 or later recommended)
- MySQL Workbench or any SQL client
- Git (optional, to clone the repo)

### 🧪 Import the Database

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/clinic-booking-db.git
   cd clinic-booking-db
2. Open MySQL Workbench or your preferred MySQL interface.

3. Run the clinic_booking_system.sql file:

Either use SOURCE in MySQL CLI:
   ```bash
   SOURCE /path/to/clinic_booking_system.sql;
```
---

## 🖼️ Entity Relationship Diagram (ERD)

ERD shows all relationships between Patients, Doctors, Appointments, Users, Prescriptions, Medications, Tests, Payments, and more.

✅ Use Case Chosen:
Clinic Booking System

🗃️ Entities Involved:
- Patients

- Doctors

- Appointments

- Departments

- Prescriptions

- Medications

🔗 Relationships:

- One doctor belongs to one department (Many-to-One)

- One department can have many doctors (One-to-Many)

- One patient can have many appointments (One-to-Many)

- One doctor can have many appointments (One-to-Many)

- Each appointment can have one prescription (One-to-One)

A prescription can contain multiple medications (Many-to-Many)

---
## 🙋‍♂️ Contributing
Feel free to fork this repo and suggest improvements, such as:

Stored procedures or triggers

Indexing for performance

Views for complex reports

## 📜 License
This project is licensed under the MIT License.

## ✍️ Author
Wilbrodah

GitHub: @Wilbrodah24

Email: wilbrodahmakhanu@gmail.com

