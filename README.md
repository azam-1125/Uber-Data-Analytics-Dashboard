# Uber-Data-Analytics-Dashboard

## 🔍 Objective
This project aims to analyze historical ride booking data for the NCR region to identify:
- Key booking trends and patterns
- Factors influencing booking statuses (e.g., completed, cancelled, incomplete)
- Performance metrics related to rides (e.g., average value, distance, ratings)
- Strategic opportunities for operational improvement and customer satisfaction

It concludes with an **interactive Power BI dashboard** and a **summary of insights** designed for business decision-makers.

---

## 🗃️ Dataset Overview
- **Source**: Google Sheets
- **File**: `ncr_ride_bookings-ncr_ride_bookings.csv`
- **Size**: ~150,000 rows | ~21 columns
- **Content**:
  - Date, Time, Booking ID, Booking Status
  - Customer ID, Vehicle Type
  - Pickup Location, Drop Location
  - Avg VTAT, Avg CTAT
  - Cancelled Rides by Customer, Reason for cancelling by Customer
  - Cancelled Rides by Driver, Driver Cancellation Reason
  - Incomplete Rides, Incomplete Rides Reason
  - Booking Value, Ride Distance
  - Driver Ratings, Customer Rating, Payment Method

**Key Features of Dataset**:
- Time-based booking data enabling trend analysis.
- Detailed booking statuses and reasons for cancellations/incomplete rides.
- Ride-specific metrics like booking value, distance, and average turnaround times.
- Customer and driver ratings for service quality assessment.
- Geographical information for pickup and drop locations.

---

## 🛠️ Tools & Technologies Used
| Tool            | Purpose                                     |
|-----------------|---------------------------------------------|
| Microsoft Excel | Data cleaning, PivotTables, basic dashboards |
| Power BI        | Interactive dashboards, DAX measures, storytelling |
| Power Query     | Data transformation and loading       |
| DAX             | Creating KPIs and custom metrics      |

---

## 📆 Project Timeline & Weekly Breakdown

### 🔹 Week 1: Data Collection & Preprocessing (Excel)
- Imported data into Excel.
- Cleaned missing and inconsistent values using Excel's data cleaning features.
- Standardized date formats and categories.
- Performed initial exploration using **Excel PivotTables** and basic charts.

### 🔹 Week 2: KPI Design & Excel Visualization / Power BI Setup
- Defined key metrics:
  - Total Bookings
  - Bookings by Status
  - Monthly and Regional Trends
  - Average Ride Value and Distance
- Created Excel dashboards with charts, slicers, and tables for initial insights.
- Began Power BI setup: data model import via Power Query and layout design.

### 🔹 Week 3: Power BI Dashboard Development
- Built dynamic and **interactive visualizations** in Power BI:
  - Slicers for region, vehicle type, and time
  - Drill-down charts for detailed analysis of booking statuses and metrics
- Used DAX to create calculated fields and measures for KPIs.
- Focused on clean layout and storytelling within the dashboard.

### 🔹 Week 4: Finalization & Presentation Prep
- Polished Power BI dashboard design, color scheme, and usability.
- Created a professional **summary report** of key findings and recommendations.
- Captured dashboard screenshots for documentation and the README.
- Prepared final project delivery and presentation materials.

---

## 💡 Key Findings (Hypothetical)
- **Peak Booking Times** observed during specific hours and days, indicating demand patterns.
- **Common Cancellation Reasons** for both customers and drivers were identified, highlighting areas for service improvement.
- **Popular Vehicle Types** and their performance metrics were analyzed.
- **Booking Status Distribution** showed the proportion of successful vs. unsuccessful bookings.
- **Average Ride Metrics** provided insights into the efficiency and value of rides.

---

## 📊 Output: Power BI Dashboard
Key Components:
- **Monthly Booking Trend Line**
- **Bookings by Vehicle Type & Status**
- **Cancellation Reasons Analysis**
- **Average Ride Value and Distance**
- **Slicers** for dynamic filtering by Region, Vehicle Type, Month, and Booking Status

> ✅ Fully interactive, filterable, and designed for quick executive insights.

📸 *Final dashboard output: [Link to hypothetical screenshot] (Replace with actual link if available)*

---

## 📝 Recommendations (Hypothetical)
1.  **Optimize Driver Allocation**: Based on peak booking times and popular vehicle types, optimize driver allocation to reduce 'No Driver Found' instances and improve service speed.
2.  **Address Cancellation Root Causes**: Investigate and implement solutions for the most common customer and driver cancellation reasons to increase booking completion rates.
3.  **Enhance Vehicle Type Performance**: Analyze the performance of different vehicle types and implement strategies to improve the efficiency or profitability of underperforming types.
4.  **Improve Customer and Driver Satisfaction**: Use insights from ratings and cancellation reasons to implement targeted programs for improving the experience of both customers and drivers.

---
![Alt Text](https://github.com/azam-1125/Uber-Data-Analytics-Dashboard/blob/c29953d0037a25597a75b823a357428a606ba369/dashboard.png)
