# fcc-Salon-Appointment-Scheduler

💇 *Salon Appointment Scheduler*

A Bash and PostgreSQL project built as part of the freeCodeCamp Relational Database Certification.

This project is a command-line salon booking system that allows customers to schedule appointments for different salon services. Customer and appointment data are stored and managed using PostgreSQL.

---

## 🚀 Features

- Interactive Bash script interface
- PostgreSQL database integration
- Appointment scheduling system
- Customer record management
- Existing customer lookup using phone number
- Automatic customer creation for new users
- Relational database structure
- Input validation for services

---

## 🛠️ Technologies Used

- PostgreSQL
- SQL
- Bash Scripting
- Git
- GitHub
- Linux Terminal

---

## 🗂️ Database Structure

The database contains the following tables:

| Table | Description |
|---|---|
| services | Stores salon services offered |
| customers | Stores customer information |
| appointments | Stores appointment bookings |

---

## 🔗 Entity Relationships
Customers → Appointments ← Services

-One customer can have many appointments
-One service can have many appointments
-Each appointment belongs to one customer and one service

📚 Concepts Practiced

This project helped practice:

-Bash scripting
-PostgreSQL commands
-SQL queries
-Primary and Foreign Keys
-Relational database design
-User input handling
-Conditional statements in Bash
-Database interaction using psql

🎯 Certification Project

Completed as part of the freeCodeCamp Relational Database Certification.
