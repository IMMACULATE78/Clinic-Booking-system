# Clinic Booking System Database

## Description
This project is a full-featured **Clinic Booking System** built using **MySQL**. It allows a healthcare clinic to manage patient information, doctor records, appointments, services offered, and payment tracking — all in a well-structured relational database with proper constraints and relationships.

## Features
- Patient and doctor registration
- Appointment scheduling and status tracking
- Service offerings and associated fees
- Payment records for each appointment
- Clear relational structure with:
  - 1-to-Many (Doctors to Appointments)
  - Many-to-Many (Appointments to Services)
  - 1-to-1 (Appointments to Payments)

## How to Set Up
1. **Clone or download** this repository.
2. Open your **MySQL Workbench** or preferred SQL tool.
3. Run the script file:  
   ```bash
   clinic_booking_system.sql
