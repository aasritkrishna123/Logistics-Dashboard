# 🚚 SwiftRoute Logistics Analytics Dashboard (Power BI Project)

This project presents an **interactive logistics analytics dashboard** built using **Power BI** to monitor delivery operations, hub performance, driver efficiency, and vehicle utilization.

The dashboard provides a centralized view of key operational KPIs and enables management to identify **delivery delays, capacity utilization, fleet performance, and workforce efficiency**.

This project is highly relevant for **Data Analyst, BI Analyst, Power BI Developer, Operations Analyst, and Supply Chain Analytics roles**.

---

## 🎯 Project Objectives

- Monitor overall **logistics and delivery performance**
- Track **total orders, on-time delivery rate, CSAT, and average delivery time**
- Analyze **hub capacity and operational performance**
- Evaluate **driver experience, ratings, and delivery delays**
- Monitor **vehicle utilization and maintenance risk**
- Identify operational areas requiring improvement
- Support **data-driven logistics and resource planning**

---

## 🧩 Problem Statement

SwiftRoute Logistics needs an efficient way to monitor its delivery operations across **hubs, drivers, and vehicles**.

Management requires visibility into order volumes, delivery performance, customer satisfaction, hub capacity, driver delays, and vehicle utilization to identify operational bottlenecks and improve service quality.

The objective of this project is to develop an **interactive Power BI dashboard** that consolidates these operational metrics into actionable insights for better **capacity planning, workforce management, fleet optimization, and delivery performance improvement**.

---

## 📦 Dataset / Business Requirements

The dashboard is designed around logistics operational data covering:

- Orders and delivery performance
- Hub capacity and order processing
- Driver experience and performance ratings
- Driver delays and monthly deliveries
- Vehicle availability and maintenance status
- Vehicle models and utilization
- Vehicle breakdowns
- Vehicle types and order distribution

The dashboard supports analysis by:

- **Year**
- **Month**
- **Vehicle Type**
- **Vehicle Status**
- **Driver**
- **Hub**
- **Vehicle**

---

## 🧠 Dashboard Workflow

### 🔹 1. Data Preparation

- Prepared logistics data for Power BI analysis
- Organized operational attributes for hub, driver, vehicle, and order analysis
- Created fields required for monthly and year-wise analysis
- Prepared data for KPI and performance calculations

### 🔹 2. Data Modeling

- Built relationships between operational entities
- Structured the model for hub, driver, vehicle, and order analysis
- Designed the model to support interactive filtering and drill-down analysis

### 🔹 3. DAX Measures & KPIs

Created business-focused measures for:

- Total Orders
- Previous Month Orders
- Month-over-Month (MoM) Order Growth
- On-Time Delivery Rate
- Previous Month On-Time Delivery Rate
- CSAT %
- Previous Month CSAT %
- Average Delivery Time
- Previous Month Average Delivery Time
- Hub Performance
- Driver Performance
- Vehicle Utilization
- Breakdown Analysis

### 🔹 4. Dashboard Development

The solution consists of four major analytical views:

- **SwiftRoute Logistics Overview**
- **Hubs Overview**
- **Drivers Overview**
- **Vehicles Overview**

Interactive slicers allow users to analyze performance by **year, month, vehicle type, vehicle status, driver, and other operational dimensions**.

---

## 📊 Dashboard Pages

### 🔹 1. Logistics Overview

The overview page provides a high-level snapshot of overall logistics performance.

Key KPIs include:

- Total Orders
- On-Time Delivery Rate
- Customer Satisfaction (CSAT)
- Average Delivery Time

It also provides comparative analysis across:

- Hubs
- Drivers
- Vehicles

---

### 🔹 2. Hubs Overview

The Hubs Overview focuses on operational capacity and hub efficiency.

Key analysis includes:

- Total Number of Hubs
- Orders Processed vs Hub Capacity
- Hub Performance Ranking
- Daily Hub Order Processing Time

These visuals help identify hubs operating efficiently and areas where capacity or processing time may require attention.

---

### 🔹 3. Drivers Overview

The Drivers Overview evaluates workforce performance and driver-level operational efficiency.

Key analysis includes:

- Total Number of Drivers
- Experience vs Performance Rating
- Drivers with Most Delays
- Individual Driver Profile
- Hire Date
- Years of Experience
- Star Rating
- Monthly Delivery Trends

The driver profile allows management to select an individual driver and analyze their performance for the selected month.

---

### 🔹 4. Vehicles Overview

The Vehicles Overview focuses on fleet availability, utilization, and maintenance.

Key analysis includes:

- Total Number of Vehicles
- Active vs Maintenance Vehicles
- Total Orders by Vehicle Model
- Vehicle Age vs Breakdown
- Breakdown by Vehicle Code
- Breakdown by Vehicle Model
- Orders by Vehicle Type

This helps identify aging vehicles, high-utilization models, and vehicles requiring maintenance attention.

---

## 📊 Key Insights (Dashboard Findings)

### 🔹 Overall Logistics Performance

- The dashboard records **1,130 total orders** for February 2024.
- The **On-Time Delivery Rate is 81.6%**, indicating that a meaningful portion of deliveries may still require improvement.
- **Customer Satisfaction (CSAT) is 86.5%**, showing a relatively strong customer experience.
- Average delivery time is **35.94 hours** for the selected period.

### 🔹 Hub Performance

- SwiftRoute operates across **6 hubs**.
- **San Antonio Hub** has the highest hub performance score at **86.5%**.
- **El Paso Hub** follows closely at **85.6%**.
- **Dallas Main Hub** records **81.8%**, while Austin Hub records **80.8%**.
- **Fort Worth Hub** and **Houston Hub** have comparatively lower performance scores of **80.2%** and **78.9%**, respectively.
- The comparison between orders processed and hub capacity helps identify opportunities for better workload distribution.

### 🔹 Driver Performance

- The dashboard provides visibility into **55 drivers** at the overall level.
- Driver experience and performance ratings can be analyzed together to identify performance patterns.
- The **Drivers with Most Delays** view highlights individuals requiring closer operational review or coaching.
- Individual driver profiles provide additional visibility into **experience, rating, hire date, and monthly deliveries**.

### 🔹 Vehicle Performance

- The fleet contains **45 vehicles**.
- **33 vehicles (73.33%) are active**, while **12 vehicles (26.67%) are under maintenance**.
- **Mercedes Sprinter** handles the highest number of orders with **216 orders**.
- **Freightliner M2** follows with **207 orders**, making both models highly utilized.
- Ford Transit records **162 orders**, followed by International DuraStar with **139 orders**.
- Vehicle age versus breakdown analysis helps identify aging vehicles that may require preventive maintenance.

### 🔹 Operational Monitoring

- Monthly order trends allow management to identify changes in delivery workload.
- Hub processing-time analysis highlights differences in daily operational turnaround.
- Vehicle breakdown analysis can help prioritize maintenance activities.
- Combining order, driver, hub, and vehicle metrics provides a broader view of logistics performance.

---

## 💡 Business Recommendations

### 1️⃣ Improve On-Time Delivery Performance

- Analyze the root causes of delayed deliveries.
- Focus on hubs and drivers with higher delay rates.
- Align driver and vehicle availability with order demand.

### 2️⃣ Optimize Hub Capacity

- Compare order volume against available hub capacity.
- Redistribute workload where hubs experience capacity imbalance.
- Investigate hubs with comparatively lower performance scores.

### 3️⃣ Strengthen Driver Performance

- Provide targeted coaching for drivers with frequent delays.
- Monitor the relationship between experience and performance ratings.
- Use individual driver profiles for performance reviews.

### 4️⃣ Optimize Fleet Utilization

- Prioritize highly utilized vehicle models for operational planning.
- Monitor vehicles with frequent breakdowns.
- Increase preventive maintenance for aging vehicles.

### 5️⃣ Improve Customer Experience

- Monitor CSAT alongside delivery performance.
- Identify whether delivery delays are contributing to lower customer satisfaction.
- Track monthly changes to ensure operational improvements translate into better customer outcomes.

---

## 🛠️ Tools & Technologies Used

- **Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Data Visualization**
- **KPI & Operational Analytics**
- **Logistics & Supply Chain Analytics**

---

## 📸 Dashboard Preview
https://github.com/aasritkrishna123/Logistics-Dashboard/blob/main/ChatGPT%20Image.png
### 
