🚖 OLA Cancellations Insights Dashboard

A dynamic, interactive data analytics dashboard built to identify the key reasons and trends behind ride cancellations in OLA’s cab service — enabling data-driven insights to improve customer satisfaction and operational efficiency.

🧭 Short Description / Purpose

The OLA Cancellations Insights Dashboard is a visually engaging Power BI project that analyzes historical ride data to uncover cancellation patterns, root causes, and performance metrics. This tool helps identify how factors like ride type, location, time, and customer-driver behavior influence cancellation rates—empowering business decisions for better service optimization and user experience.

⚙️ Tech Stack

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Main data visualization platform used to design the interactive dashboard.

📂 Excel – Used for initial data exploration, cleaning, and pre-processing.

🧮 SQL (Structured Query Language) – Applied for data extraction, transformation, and analysis using complex queries.

🔍 Power Query – Used within Power BI to reshape, clean, and merge datasets.

🧠 DAX (Data Analysis Expressions) – Created calculated columns and measures to support dynamic KPIs and visuals.

📁 File Format – .pbix for Power BI dashboard, .xlsx for cleaned dataset, .sql for query scripts.

📊 Data Source

Source: Hypothetical OLA Ride Dataset (extracted from Kaggle and chat gpt).

The dataset contains records of OLA rides such as:

Booking ID, Customer ID, Driver ID

Ride Type (Mini, Sedan, Prime, Bike, etc.)

Pickup & Drop Location

Date and Time of Booking

Ride Status (Completed / Cancelled / No-show)

Cancellation Reason (Customer-side / Driver-side / Technical)

Fare Estimate, Distance, Duration

This structured dataset was used to perform exploratory data analysis, cancellation pattern identification, and visualization.

🌟 Features / Highlights
• Business Problem

OLA faces a significant challenge in understanding the root causes of ride cancellations, which directly affect customer satisfaction, driver utilization, and revenue. The business team needed a unified analytical view to track cancellation trends and take actionable decisions.

• Goal of the Dashboard

To develop an interactive and insightful analytical dashboard that:

Identifies major reasons behind ride cancellations.

Highlights temporal trends (daily, weekly, hourly) in cancellations.

Reveals customer vs. driver cancellation patterns.

Enables OLA’s operation and strategy teams to make data-driven decisions to reduce cancellations and improve service reliability.

• Walkthrough of Key Visuals

📌 Key KPIs (Top Panel)

Total Bookings

Completed Rides

Cancelled Rides

% Cancellation Rate

Avg Ride Distance

Avg Ride Duration

🕓 Cancellation Trend Over Time 

Displays how cancellation rates fluctuate by days helping identify peak cancellation periods.

🌍 Cancellation by Location 

Interactive map highlights hotspot zones with the highest cancellation frequency.

🚗 Ride Type Comparison 

Compares cancellation rates across ride categories (Auto, Mini, Prime, Sedan, Bike) to identify service types most affected.

👥 Cancellation Reason Breakdown 

Segments cancellations by Customer-side, Driver-side, and System-side reasons for quick understanding.

🧭 Time & Distance vs. Cancellation 

Visual correlation between ride distance, trip duration, and likelihood of cancellation.

🎛️ Interactive Filters 

Allow filtering by city, ride type, time range, driver rating, and day of week.

Fully clickable interface with dynamic KPIs that adjust based on user selections.

• Business Impact & Insights

Customer Retention: Identified key periods and regions with high customer cancellations, enabling OLA to design targeted offers and incentives.

Driver Performance Optimization: Revealed trends where driver-side cancellations were more frequent, suggesting areas for training or incentive improvement.

Operational Efficiency: Provided visibility into technical issues or peak-hour mismatches that increase cancellation probability.

Strategic Decision-Making: Helped management track service reliability KPIs, leading to better policy and operational changes.

📈 Outcome / Learning

Through this project, I successfully performed data cleaning, transformation, EDA, and dashboard creation from raw data to insight delivery.
It demonstrates my ability to combine SQL querying, Excel preprocessing, and Power BI visualization to build data-driven business intelligence solutions.

🖼️ Screenshots / Demos

Below are sample visuals from the Power BI dashboard

Dashboard Overview - https://github.com/nadeem786-stack/ola---identified-the-reason-and-trend-of-cancellation-rides/blob/main/ola-overall.png

Vehical type - https://github.com/nadeem786-stack/ola---identified-the-reason-and-trend-of-cancellation-rides/blob/main/ola%20-%20vehical%20type.png

revenue - https://github.com/nadeem786-stack/ola---identified-the-reason-and-trend-of-cancellation-rides/blob/main/ola%20-%20revenue.png

Cancellations - https://github.com/nadeem786-stack/ola---identified-the-reason-and-trend-of-cancellation-rides/blob/main/ola-cancellation.png

Ratings - https://github.com/nadeem786-stack/ola---identified-the-reason-and-trend-of-cancellation-rides/blob/main/ola-ratings.png
