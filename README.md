 Oyo Sales Insight Analysis in Power BI

 📌 Project Overview
This project aims to analyze the sales performance of Oyo hotels using Power BI. The insights will help Oyo make data-driven decisions to improve its market share, optimize revenue, and enhance customer satisfaction. The project includes data loading, transformation, dashboard creation, and extracting actionable insights.

 🏨 Domain: Hospitality | Function: Revenue

 🚀 Problem Statement
AtliQ Grands, a luxury and business hotel chain in India, is losing market share due to strategic moves by competitors and ineffective decision-making. To address this, they have decided to incorporate Business and Data Intelligence. Since they lack an in-house analytics team, they have hired a third-party service provider (us) to analyze historical data and generate insights.

 🔹 Key Tasks:
- Create metrics for performance analysis.
- Develop an interactive dashboard as per stakeholder requirements.
- Identify additional insights beyond the provided mock-up.

---

 📊 Data Preparation & Processing
 🔹 Data Sources:
The analysis is based on five CSV files:
1. dim_date – Date-related information (e.g., weekdays/weekends, month, year, week number).
2. dim_hotels – Hotel properties with categories, city locations, and names.
3. dim_rooms – Room types and classifications (Standard, Elite, Premium, Presidential).
4. fact_aggregated_bookings – Successful bookings, capacity, check-in dates, etc.
5. fact_bookings – Detailed booking transactions, revenue, platform used, ratings, and booking status.

 🔹 Data Cleaning & Transformation:
- dim_date: Removed incorrect `day_type` column and recalculated it based on industry standards.
- dim_rooms: Corrected column headers using "Use First Row as Headers".
- fact_bookings: Adjusted `revenue_realized` by deducting 40% for cancellations.
- Merged datasets to ensure seamless analysis.

---

 📊 Power BI Implementation
 🔹 Steps Followed:
1. Created a folder for all raw CSV files.
2. Used Power BI’s Get Data feature to import them.
3. Expanded datasets and performed Power Query transformations.
4. Built a data model linking relevant tables via primary and foreign keys.
5. Created measures & calculated columns for key KPIs.
6. Designed an interactive dashboard with relevant filters and visualizations.

---

 📌 Key Metrics & Insights
 🔹 Metrics Created:
- Total Revenue Generated
- Revenue Realized (after cancellations)
- Booking Trends (Daily, Weekly, Monthly)
- Occupancy Rate by Room Type
- Cancellation Rate & Reasons
- Top Performing Cities & Hotels
- Customer Ratings & Feedback Trends
- Booking Platform Performance (Website, App, Third-party, etc.)

 🔹 Additional Insights Identified:
- Identified peak booking periods and low-demand seasons.
- Found cities with high cancellation rates and potential reasons.
- Analyzed customer behavior trends to optimize pricing strategies.

---

 📌 Conclusion & Recommendations
 🔹 Key Findings:
- Revenue losses were primarily due to high cancellation rates.
- Some cities had low occupancy despite high demand, indicating supply issues.
- Certain room types were underutilized, suggesting pricing or marketing gaps.

 🔹 Strategic Recommendations:
- Implement dynamic pricing to maximize revenue in peak seasons.
- Improve cancellation policies to reduce last-minute losses.
- Optimize marketing efforts on high-performing platforms.
- Enhance customer experience based on ratings and feedback analysis.

---

 🎯 Future Enhancements
- Incorporate Real-Time Data Integration.
- Add Predictive Analytics for revenue forecasting.
- Implement Geo-Spatial Analysis for location-based insights.
- Explore integration with AI-driven recommendation systems for personalized offers.

---

 📌 Reference
This project was made with reference to a project on YouTube uploaded by Codebasics. https://www.youtube.com/watch?v=hhZ62IlTxYs&list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9

 ---

 📌 Final Dashboard
 
![Final Dashboard](final_dashboard.jpg)

![final dashboard](https://github.com/user-attachments/assets/a3abd419-c3f8-4af3-99a4-e5d2398dc183)

---

Thank you for exploring this project! 🚀

--- 
