# Ride Booking Data Analysis – Bengaluru, July 2024

## 📁 Project Overview

This project analyzes simulated ride-booking data for 40,000+ records in the city of **Bengaluru** during **July 2024**, using **Excel**, **MySQL**, and **Power BI**. It focuses on basic trend analysis, cancellation patterns, and ride distribution to simulate a real-world ride-hailing platform’s operations over a one-month period.

---

## 🧰 Tools Used

- **Excel** – Data entry and formatting
- **MySQL** – Querying and simple data aggregation
- **Power BI** – Interactive dashboard for analysis

---

## 📊 Dashboard Features

This project simulates real-world ride-calling data for Bengaluru and includes 20+ fields such as:

- **Date & Time:** Tracks booking trends and peak hours  
- **Booking ID:** Unique 10-digit IDs (e.g., `CNR12345678`)  
- **Booking Status:** Successful, Cancelled by Customer/Driver, or Incomplete  
- **Vehicle Type:** Auto, Bike, Mini, Prime Sedan, etc.  
- **Pickup & Drop Locations:** Randomized across 50 prominent areas in Bengaluru  
- **Cancellation Reasons:** Includes detailed reasons for cancellations  
- **Ride Metrics:** Vehicle Time to Arrive (VTAT), Customer Time to Arrive (CTAT), Ride Distance, etc.  
- **Payment Methods & Booking Values:** Categorized under specific ranges for comparison

> 📷 Screenshots will be added below after upload

---

## 📁 Files Included

| File Name                         | Description                           |
|-----------------------------------|---------------------------------------|
| `Dataset_40000_Bookings.xlsx`     | Raw dataset used for the analysis     |
| `OLA_project_dashboard.pbix`      | Power BI file with dashboard visuals  |
| `Ola_project.sql`                 | SQL queries for aggregation/filtering |
| `README.md`                       | This documentation file               |

---

## 🧠 Sample SQL Queries

Count total bookings:
```sql
SELECT COUNT(*) AS Total_Bookings
FROM bookings;

Cancelled rides (by customer or driver):
```sql
SELECT COUNT(*) AS Cancelled_Bookings
FROM bookings
WHERE Booking_Status IN ('Canceled by Customer', 'Canceled by Driver');

---

