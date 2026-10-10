# 🚖 Ola Ride Booking Analysis

An interactive **Power BI dashboard** that analyzes **1,03,024 Ola ride bookings (July 2024)** to track bookings, revenue, cancellations, vehicle performance, and customer & driver ratings.

---

## 📌 Project Overview

**Purpose:** To turn raw ride booking data into clear, actionable insights that help understand ride demand, revenue by vehicle type and payment method, cancellation reasons, and rating trends.

**Key questions answered:**
- How many rides were booked, successful, and cancelled?
- Which vehicle types earn the most booking value and travel the longest distances?
- Which payment methods drive the most revenue?
- Why do customers and drivers cancel rides?
- How are drivers and customers rating each vehicle type?

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Data Visualization | Power BI Desktop |
| Data Modeling & KPIs | DAX |
| Data Cleaning & Transformation | Power Query |
| Data Source | Microsoft Excel |

---

## 📂 Data Source

- **Dataset:** Ola ride booking data for **July 2024** (01-07-2024 to 31-07-2024), in Excel format
- **Size:** 1,03,024 booking records
- **Coverage:** Pickup and drop locations across Bengaluru
- **Main columns:** Date, Time, Booking_ID, Booking_Status, Customer_ID, Vehicle_Type, Pickup_Location, Drop_Location, V_TAT, C_TAT, Canceled_Rides_by_Customer, Canceled_Rides_by_Driver, Incomplete_Rides, Incomplete_Rides_Reason, Booking_Value, Payment_Method, Ride_Distance, Driver_Ratings, Customer_Rating

---

## ⚙️ Project Workflow

1. **Data Import:** Loaded the Excel dataset into Power BI.
2. **Data Cleaning:** Cleaned and transformed the data using Power Query (data types, missing values, inconsistencies).
3. **Data Modeling:** Created DAX measures such as Average Booking Value, Cancelled Bookings, Cancellation Rate %, and Success Rate %.
4. **Dashboard Design:** Built a 5-page interactive dashboard with navigation, date slicer, and vehicle-type slicer.
5. **Insights:** Analyzed visuals to find booking, revenue, cancellation, and rating patterns.

---

## 📊 Dashboard Pages

| Page | What it shows |
|---|---|
| **Overall** | KPI cards (Total Booking, Average Booking Value, Total Booking Value, Success Rate %, Cancellation Rate %), booking status breakdown, ride volume over time, vehicle-type slicer |
| **Vehicle Type** | Total booking value, success booking value, average distance, and total distance for each vehicle type |
| **Revenue** | Revenue by payment method, ride distance distribution by day, top customers by booking value |
| **Cancellation** | Total, success, and cancelled bookings, cancellation rate, and cancellation reasons by customers and by drivers |
| **Ratings** | Driver and customer ratings by vehicle type |

**Vehicle types analyzed:** Prime Sedan, Prime SUV, Prime Plus, Mini, Auto, Bike, E-Bike

---

## ✨ Features

- Interactive dashboard with dynamic date-range and vehicle-type filtering
- Sidebar navigation across 5 report pages
- KPI cards for bookings, booking value, success rate, and cancellation rate
- Booking status breakdown: Success, Cancelled by Driver, Cancelled by Customer, Driver Not Found
- Daily ride volume trend and ride distance distribution
- Revenue comparison across payment methods (Cash, UPI, Credit Card, Debit Card)
- Detailed cancellation reason analysis for both customers and drivers
- Driver and customer rating comparison across all vehicle types

---

## 🔍 Key Insights

- Of **1,03,024** bookings in July 2024, about **63,967** were successful and **28,933** were cancelled, giving a **28.08% cancellation rate**.
- **Top customer cancellation reason:** "Driver is not moving towards pickup" (**30.24%**), followed by "Driver asked to cancel" (**25.43%**).
- **Top driver cancellation reason:** "Personal & car related issues" (**35.49%**), followed by "Customer related issue" (**29.36%**).
- **Cash** and **UPI** generate most of the revenue, while credit and debit cards contribute very little.
- **Prime Sedan** has the highest total and successful booking value (**8.30M** and **5.22M**).
- **Auto** rides are much shorter (about **10 km** average) than other vehicle types (about **25 km**).
- Driver and customer ratings are very consistent across vehicle types, at about **4.0** out of 5.

---

## 🌟 Highlights

- Cleaned and transformed raw data using **Power Query**
- Built **DAX measures** for business KPIs
- Analyzed **1 lakh+ records** in a single interactive report
- Covered bookings, revenue, vehicle performance, cancellations, and ratings in one dashboard
- Clean, branded, user-friendly design built for data-driven decision-making

---
📁 Screen Shot:
Example: ![Dashboard Preview](https://github.com/KaranShinde016/Ola-Ride-Booking-Analysis-Dashboard/edit/main/README.md)

---
## 📁 Repository Structure

```
Ola-Ride-Booking-Analysis/
│
├── Ola_Dashboard.pbix        # Power BI file
├── images/                   # Dashboard screenshots
└── README.md
```

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the date and vehicle-type slicers and the sidebar to explore each page.

---

## 👤 Author

**Karan Shinde**
Data Analyst | SQL | Python | Power BI | Tableau | Excel

📧 karanshinde1608@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/karan-shinde-56a35529a)
