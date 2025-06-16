# Ride Booking Data Analysis – Bangalore, July 2024

## 📁 Project Overview

This project analyzes ride booking data for Bangalore during **July 2024** using **Excel**, **MySQL**, and **Power BI**. The goal is to observe basic trends in bookings, cancellations, and ride types over the month.

---

## 🔧 Tools Used

- **Excel** – Data cleaning and formatting
- **MySQL** – Data querying and aggregation
- **Power BI** – Dashboard and basic visuals

---

## 📊 Dashboard Features

> _(Add screenshots below after uploading images)_

- Total number of bookings and daily trends
- Cancelled rides by customers and drivers
- Count of rides by ride type
- Simple summary visuals (bar charts, tables)

---

## 🗃 Dataset Info

- **City:** Bangalore  
- **Month:** July 2024  
- **Source Format:** Excel  
- **Imported Into:** MySQL for querying  
- **Final Output:** Power BI dashboard (`.pbix`)

---

## 🧠 Sample SQL Queries Used

Count total bookings:

```sql
SELECT COUNT(*) AS Total_Bookings
FROM bookings;
