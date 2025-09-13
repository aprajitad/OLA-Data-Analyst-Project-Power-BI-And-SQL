
# 🚖 OLA Data Analyst Project – SQL & Power BI

This project analyzes **OLA ride-booking data** using **SQL** and **Power BI** to track ride volumes, customer behavior, driver performance, revenue, and cancellations. The insights help optimize operations, improve service quality, and identify top customers and vehicle types.

---

## 📂 Database & SQL

* **Database:** Ola
* **Tables:** Bookings, Customers, Drivers
* **Key Columns:** Booking\_ID, Customer\_ID, Vehicle\_Type, Booking\_Status, Ride\_Distance, Payment\_Method, Ratings, Booking\_Value
* **Views:** Predefined SQL views simplify querying
* **Sample Insights:**

  * Top-performing customers
  * Average ratings and distances
  * Trends in cancellations
  * Revenue from successful rides

**Setup:**

```sql
CREATE DATABASE Ola;
USE Ola;
-- Import bookings.csv into MySQL Workbench
SELECT * FROM bookings LIMIT 10;
```

**SQL File:** `Ola DA Project SQL.sql` (4 KB)

---

## 📊 Power BI Analysis

* **Features:**

  * Ride Volume trends
  * Booking Status Breakdown
  * Top 5 Vehicle Types
  * Revenue by Payment Method
  * Cancellation Reasons
  * Customer & Driver Ratings
* **Tools:** Power BI, SQL, Excel/CSV
* **Project Steps:** Requirement gathering → Data cleaning → Modeling → DAX → Dashboard → Insights
* **Dashboard File:** `Ola DA Project.pbix` (3.96 MB)

---

## 📈 Key Metrics & KPIs

* Total & Average Sales
* Ride counts
* Average Ratings
* Ride Distance distribution
* Top 5 Customers & Vehicle Types

---

## 📋 How to Use

1. Import `bookings.csv` into MySQL and run SQL script.
2. Open `Ola DA Project.pbix` in Power BI to explore dashboards.

---

## 📧 Contact

**Aprajita Dixit**
Email: dixitaprajita42@gmail.com
Portfolio: \[Link]

---

## 🙌 Acknowledgments

Thanks to **Top VarSity** for tutorial guidance.

---
