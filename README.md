# Uber Trip Data Analysis Dashboard

## 📊 Overview
This project is an end-to-end data analysis of Uber trip data. The goal was to build an interactive **Power BI dashboard** to uncover patterns in trip demand, analyze booking values, and provide actionable insights to optimize driver allocation and pricing strategies.

## 🎯 Business Objective
To help Uber operations analysts:
- Identify **peak demand hours** and **high-value locations** to minimize wait times and maximize driver efficiency.
- Understand key metrics like **total bookings, revenue, and average trip distance**.
- Make data-driven decisions to improve operational efficiency and customer satisfaction.

## 📁 Data Sources
The analysis was performed on a simulated Uber dataset containing over **100,000 trip records** with the following key attributes:
- `Trip ID`, `Pickup Date`, `Pickup Hour`
- `Vehicle Type` (UberX, Uber Black, UberXL, etc.)
- `Payment Type` (Cash, Uber Pay)
- `Number of Passengers`, `Trip Distance (miles)`
- `Booking Value ($)`, `Pickup Location`

## 🛠️ Tools Used
- **Microsoft Power BI:** For creating interactive visualizations and dashboards.
- **DAX (Data Analysis Expressions):** For creating calculated measures and columns.
- **Excel:** For initial data inspection and validation.
- **Data Analysis:** Trend analysis, time series analysis, summary statistics.

## 📈 Key Features of the Dashboard
The Power BI report consists of three main pages:

### 1. Overview Analysis
- High-level KPIs: **Total Bookings (103.7K), Total Booking Value ($1.6M), Average Booking Value ($14.98)**
- Total Trip Distance (349K miles) and Average Trip Distance (3 miles)

### 2. Time Analysis
- **Total Bookings by Pickup Hour:** A visual representation to identify peak and off-peak hours.
- **Time-based trends** to understand daily demand cycles.

### 3. Details
- A detailed table view of raw data for granular analysis.
- Filters by vehicle type, payment type, and location.

## 🔍 Insights & Findings
- **Peak Hours:** The highest number of trips occur between 5:00 PM - 7:00 PM (evening rush hour).
- **Most Popular Vehicle Type:** UberX is the most frequently booked vehicle category.
- **Revenue Analysis:** A small percentage of longer-distance trips contributes significantly to the total booking value.
- **Payment Method:** A split between cash and digital payments (Uber Pay) exists, with digital payments being more common for scheduled trips.

## 📸 Dashboard Preview

### Overview & Time Analysis
![Time Analysis Dashboard](images/Time%20Analysis.jpg) <!-- Link to your uploaded screenshot -->

### Detailed Data View
![Details Dashboard](images/Details.jpg) <!-- Link to your uploaded screenshot -->

## 🚀 How to Use This Project
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MohanNellore/Uber-Trip-Analysis.git
    ```
2.  **Open the Dashboard:** The main analysis file is `Uber_Trip_Analysis.pbix` and can be opened with Microsoft Power BI Desktop.
3.  **Interact with the Dashboard:** Use the filters and slicers in Power BI to explore different dimensions like time, vehicle type, and location.

## 📫 Contact
**Mohan Nellore**
- Email: mohannellore17@gmail.com
- LinkedIn: [linkedin.com/in/mohan-nlr](https://linkedin.com/in/mohan-nlr)
- GitHub: [github.com/MohanNellore](https://github.com/MohanNellore)

---
*This project was completed as part of my portfolio to demonstrate skills in data analysis and business intelligence.*
