 Database Design & Implementation Project

 📘 MSc Information Technology  
Course: COMP11109 - Database Design & Implementation  
University: University of the West of Scotland  
Tool Used: Microsoft Access

---

 📌 Project Overview

This project presents the end-to-end development of an appointment scheduling system for a service-based small business. The objective was to move from paper-based operations to a modern, digital, and centralized database solution using Microsoft Access.

The system manages:
- Client records
- Employee information
- Services offered
- Appointment scheduling
- Invoicing
- Business analytics via SQL queries and reports

---

 👨‍💻 Team Members & Contributions

| Name            | Banner ID   | Contribution                         |
|-----------------|-------------|--------------------------------------|
| Shahzaib Anwar  | B01799338   | ER Data Modelling & Report Writing  |
| Noman Javed     | B01794811   | SQL Queries & Report Writing        |
| Summair Ahmed   | B01795091   | Tables & Relationships, Data Entry  |
| Umair Ali       | B01796393   | Application Forms & Interface Design |

---

 🧱 Entity-Relationship Model

The system contains the following core entities:
- Client
- Employee
- Service
- ClientAppointments
- ServicesProvided (junction for Employee–Service)
- Invoice
- InvoiceRows (junction for Appointment–Invoice)

Normalization to 3NF and referential integrity are fully enforced.



