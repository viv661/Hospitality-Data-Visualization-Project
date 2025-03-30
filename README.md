# Hospitality-Data-Visualization-Project

# Project Overview

This project involves building a KPI Dashboard for AtliQ Hotels, a company that owns multiple hotel chains across various Indian cities. The dashboard helps in identifying and tracking the source of revenue
and other key performance indicators (KPIs) from May 2022 to July 2022 data. The insights generated will assist management in making strategic business decisions.

# Business Objectives

Identify revenue sources across various dimensions.

Develop a revenue dashboard for real-time business intelligence.

Provide relevant filters to slice and dice the data.

Visualize both high-level and granular insights for better decision-making.

# Dataset & Solution Approach

# Data Sources:

3 Dimension Tables: Date, Hotel, Room

2 Fact Tables: Bookings, Aggregated Bookings


# Tools & Methodology

Power BI for data visualization and dashboard creation.

Power Query for data cleaning and transformation.

Power Pivot for establishing table relationships and data modeling.

Calculated Measures for key business KPIs.

# Key Performance Indicators (KPIs)

Revenue = Sum of revenue_realized from Bookings table (in Rs.)

Total Bookings = Count of booking_id from Bookings table

Avg Rating = Average of ratings from Bookings table

Total Capacity = Sum of capacity from Aggregated bookings table

Total Successful Bookings = Sum of successful bookings from Aggregated bookings table

Occupancy Rate = Total successful bookings / Total capacity (in %)

Total Cancelled Bookings = Count of booking_id where status = ‘cancelled’

Cancellation Rate = Total cancelled bookings / Total bookings (in %)

Avg Stay Duration = Average days stayed per booking

# Revenue Dashboard Features

The dashboard includes the following key visualizations:

Revenue by Platform: A bar chart showing revenue across various booking platforms.

Occupancy Rate: A column chart displaying occupancy percentage by weekend and weekday.

Revenue by Room Type: A doughnut chart illustrating revenue distribution by room type.

Bookings by Status: A pie chart showing booking status distribution.

KPI Table: A matrix visual (pivot table) summarizing KPIs across cities and hotels.

# Filters Available:

Month-Year

City

Booking Status

Booking Platform

# Business Insights

Mumbai generated the highest revenue, while Delhi generated the least (May - July 2022).

Occupancy rates are higher during weekends, offering an opportunity to boost weekend revenue.

70% of bookings were checked out successfully, while 5% were no-shows, meaning 75% of bookings contributed to revenue.

Cancellation reasons need to be analyzed and minimized to improve revenue.

Delhi has the highest occupancy rate (60%+), but the least revenue generation, requiring strategy adjustments.

Average rating ranges between 3.4 - 3.8, with an avg stay duration of 2.4 days per booking.

# Conclusion

This project successfully delivered a revenue dashboard for AtliQ Hotels, enabling management to analyze sales performance visually and make informed business decisions. The dashboard is interactive, providing 
tooltips, filters, and real-time insights.
