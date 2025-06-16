# Ola-Data-Analysis-Project


## 🚀 Project Overview

This data analytics project analyzes ride booking data for Bangalore during July 2024 using **Excel**, **MySQL**, and **Power BI**. The main goal is to identify booking trends, cancellation patterns, and customer behavior insights that can help improve operational efficiency and customer satisfaction for a ride-hailing platform.

---

## 🛠 Tools & Technologies Used

- **Excel** – Data cleaning and preprocessing
- **MySQL** – Data storage, querying, and transformation
- **Power BI** – Dashboard creation and interactive visualizations
- **GitHub** – Version control and portfolio showcase

---

## 📊 Key Dashboards & Insights

> _(You can add screenshots below each heading later)_

### 1. Total Bookings Overview
- Total number of rides booked in July 2024
- Breakdown by day and time
- Cancellation rate vs successful rides

### 2. Cancellations Analysis
- Number of cancellations by customers vs drivers
- Peak cancellation hours
- Cancellation reasons (if available)

### 3. Payment & Ride Type Distribution
- Ride type (Economy, Premium, etc.) wise bookings
- Payment method preferences (Cash, UPI, Wallet)

### 4. Customer Trends
- Repeat vs new customers
- Top customers by number of bookings

### 5. Geographic Insights
- Pickup and drop locations heatmap (within Bangalore)
- High-demand zones

---

## 🗃 Sample Dataset

- **Source:** Internally prepared / synthetic data representing Bangalore ride bookings
- **Time Period:** July 1 to July 31, 2024
- **Format:** `.xlsx` and exported to MySQL database

---

## 🔍 SQL Queries Used

Sample query for cancelled bookings:
```sql
SELECT COUNT(*) AS Cancelled_By_Customer
FROM bookings
WHERE LOWER(TRIM(Booking_Status)) = 'canceled by customer';
