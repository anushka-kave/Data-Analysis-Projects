🏨 Hotel Booking Analytics Dashboard
📌 Project Overview

This project analyzes hotel booking data to provide insights into performance across multiple hotels, room types, and time periods. Using Power BI, the data model was built from four key tables:

fact_aggregated_bookings → Bookings, revenue, check-ins, check-outs, rooms available

dim_hotels → Hotel details (name, category/star rating, region/city)

dim_rooms → Room type, room capacity

dim_date → Date hierarchy (day, month, quarter, year)

The goal is to provide executives, managers, and analysts with a 360° view of booking performance, identify key trends, and highlight opportunities to improve occupancy, revenue, and customer experience.

🎯 Key KPIs

Total Bookings → Number of reservations made

Total Revenue → Income generated from bookings

Total Rooms Available → Room nights available across hotels

Occupancy % → % of rooms booked vs available

ADR (Average Daily Rate) → Revenue per booking

RevPAR (Revenue per Available Room) → Revenue per available room

Total Check-ins → Number of guests who checked in

Total Check-outs → Number of guests who checked out

Cancellation Rate (%) → Estimated % of bookings not realized (derived from Bookings – Check-ins)

YoY Revenue Growth % → Growth compared to same period last year

📊 Dashboard Visuals
1. Executive Overview

KPI Cards → Revenue, Bookings, Occupancy, RevPAR, Cancellations

Line Chart → Revenue trend (Month/Year)

Bar Chart → Revenue by hotel category (Star Rating)

Map → Revenue distribution by region/city

Gauge → Cancellation %

2. Booking Analysis

Donut Chart → Booking share by room type

Line Chart → Booking trend over time (Month/Year)

Column Chart → Bookings by hotel

Heatmap (Matrix) → Bookings by month and hotel

3. Revenue & Occupancy Analysis

Combo Chart (Line + Column) → Revenue vs Occupancy % trend

Column Chart → ADR by hotel

Line Chart → YoY revenue growth %

Bar Chart → Top 5 hotels by revenue

4. Cancellations & Checkouts

Column Chart → Cancellation Rate by hotel

Line Chart → Cancellations over time

Card → Total Check-outs

Table → Bookings, Check-ins, Check-outs comparison

5. Filters / Slicers

Hotel

Room Type

Date Range (Year/Month)

Region/City

🚀 Tools Used

Power BI → Data modeling, DAX measures, dashboard building

DAX → Custom measures (Revenue, Occupancy %, ADR, RevPAR, Cancellations, YoY Growth)

SQL/Excel → Data preparation (if needed)

✅ Insights Expected

Identify peak booking periods and seasonality

Compare performance across hotel categories and locations

Track occupancy and revenue efficiency (RevPAR, ADR)

Monitor cancellations and their financial impact

Highlight top-performing hotels and room types


## 📷 Dashboard Screenshots
### Executive Overview
![Executive Overview](https://github.com/anushka-kave/Data-Analysis-Projects/blob/fc76f7b12ae6bd6739c96f4d5500ad8f3f400224/Power%20BI-Project/2025-09-23%20(2).png)

### Revenue & Occupancy Analysis
![Revenue & Occupancy Analysis](https://github.com/anushka-kave/Data-Analysis-Projects/blob/ca14180abe7d7dc5a4f9491df26c92dc6314bb78/Power%20BI-Project/2025-09-23.png)

### Booking Analysis
![[Booking Analysis](https://github.com/anushka-kave/Data-Analysis-Projects/blob/dff5a09ff3573a542821167227142d25125ef1c4/Power%20BI-Project/2025-09-23%20(3).png)
