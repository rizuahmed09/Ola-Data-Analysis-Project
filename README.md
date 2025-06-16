# Ride Booking Data Analysis – Bengaluru, July 2024

## 📁 Project Overview

This project analyzes **40 000+** simulated ride‑booking records for **Bengaluru** in **July 2024** using **Excel**, **MySQL**, and **Power BI**. The goal is to understand booking trends, cancellation patterns, and ride distribution, mirroring the day‑to‑day operations of a real ride‑hailing platform across one month.

---

## 🧰 Tools Used

* **Excel** – initial data entry & light cleaning
* **MySQL** – storage, querying, and aggregation
* **Power BI** – interactive dashboards & visuals

---

## 📊 Dashboard Features

This project tracks more than **20 fields**, including:

* **Date & Time** – booking trends & peak‑hour analysis
* **Booking ID** – unique 10‑digit IDs (e.g. `CNR12345678`)
* **Booking Status** – Successful, Cancelled (Customer/Driver), Incomplete
* **Vehicle Type** – Auto, Bike, Mini, Prime Sedan, etc.
* **Pickup & Drop Locations** – 50 prominent Bengaluru areas
* **Cancellation Reasons** – granular causes captured
* **Ride Metrics** – VTAT, CTAT, ride distance, and more
* **Payment Methods & Booking Values** – tiered for comparison

> 📷 *Screenshots will appear here once added to the repo*

---

```text
🏆 Key Features

• Overall booking success rate maintained at 62 %
• Cancellation rates
    • Customer‑initiated < 7 %
    • Driver‑initiated    < 18 %
• Demand spikes modelled on weekends & cricket‑match days
• Balanced order values
    – 70 % of rides under ₹ 500
    – 28 % of rides above ₹ 500
    – Remainder above ₹ 100
• Insights extracted
    – Higher booking values & longer distances on weekends
    – Top cancellation reasons highlighted for service tweaks
```

```text
📈 Dashboards & Insights

Power BI report pages include:
– Trend view (daily bookings & success rates)
– Cancellation analysis (driver vs customer)
– Ride‑type and payment‑method breakdowns
– KPI summary card deck for quick status checks
```

---

## 📁 Files Included

| File                          | Description                       |
| ----------------------------- | --------------------------------- |
| `Dataset_40000_Bookings.xlsx` | Raw data used for analysis        |
| `OLA_project_dashboard.pbix`  | Power BI report file              |
| `Ola_project.sql`             | SQL script & sample queries       |
| `README.md`                   | Project documentation (this file) |

---

## 🧠 Sample SQL Queries

```sql
-- 1. Total bookings\ nSELECT COUNT(*) AS Total_Bookings
FROM bookings;
```

```sql
-- 2. Cancelled rides (customer or driver)
SELECT COUNT(*) AS Cancelled_Bookings
FROM bookings
WHERE Booking_Status IN ('Canceled by Customer', 'Canceled by Driver');
```


## 📊 Dataset Highlights

Below is an example of how the dataset is structured:

| Date       | Time     | Booking ID  | Booking Status | Vehicle Type | Pickup Location | Drop Location | Booking Value | Payment Method |
| ---------- | -------- | ----------- | -------------- | ------------ | --------------- | ------------- | ------------- | -------------- |
| 2024‑07‑15 | 08:30 AM | CNR12345678 | Successful     | Prime Sedan  | Koramangala     | Whitefield    | ₹ 480         | Online         |

*(Full dataset contains 40 000+ similar rows.)*


---

## 📬 Contact

• **Email:** [yourname@example.com](mailto:yourname@example.com)
• **LinkedIn:** [https://linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)


