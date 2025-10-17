# AtliQ Grands - Revenue Analysis and Business Intelligence Dashboard

## 1. Executive Summary
[cite_start]AtliQ Grands, a leading hotel chain in India, was experiencing a decline in market share and revenue performance due to increased competition and a lack of data-driven decision-making[cite: 500, 501]. [cite_start]This Business Intelligence project was initiated to identify revenue leakages, optimize occupancy, and enable strategic planning through a comprehensive Power BI dashboard[cite: 502, 503]. [cite_start]The goal is to track revenue sources and other critical performance indicators across all properties[cite: 426, 503].

## 2. Business Objective
[cite_start]The primary objective of this project was to implement a data intelligence solution to provide actionable insights into AtliQ Grands' business operations[cite: 505].

Specific goals included:
* [cite_start]Identifying key factors that influence revenue performance[cite: 507].
* [cite_start]Developing a KPI dashboard to track revenue sources and other relevant KPIs across various dimensions[cite: 427].
* [cite_start]Empowering the management team to make strategic, data-informed business decisions[cite: 428, 509].
* [cite_start]Increasing overall revenue and market share through enhanced performance tracking[cite: 510].

## 3. Technology Stack
* [cite_start]**Microsoft Power BI** [cite: 423, 496]
* [cite_start]**Power Query** (for data cleaning and transformation) [cite: 438, 496, 515]
* [cite_start]**Power Pivot** (for data modeling) [cite: 439, 496, 516]

## 4. Solution Approach

[cite_start]The project involved collecting, cleaning, and modeling data to create an interactive dashboard for tracking key metrics[cite: 430, 431, 520].

### Data Model
[cite_start]Five tables were used: 3 dimension tables (`dim_date`, `dim_hotels`, `dim_rooms`) and 2 fact tables (`fact_bookings`, `fact_aggregated_bookings`)[cite: 436]. [cite_start]Relationships were created in Power Pivot to build a robust data model for analysis[cite: 439, 516].




### Key Performance Indicators (KPIs) Created
Several measures were created using DAX to calculate important business metrics:
* [cite_start]**Revenue**: Sum of revenue realized from the Bookings table[cite: 443].
* [cite_start]**Total Bookings**: Count of all booking IDs from the Bookings table[cite: 444, 523].
* [cite_start]**Average Rating**: Average of ratings given by customers[cite: 445, 527].
* [cite_start]**Total Capacity**: Sum of capacity from the Aggregated Bookings table[cite: 446].
* [cite_start]**Total Successful Bookings**: Sum of all successful bookings[cite: 447].
* [cite_start]**Occupancy Rate**: (Total successful bookings / Total capacity) %[cite: 450, 524].
* [cite_start]**Cancellation Rate**: (Total cancelled bookings / Total bookings) %[cite: 452, 525].
* [cite_start]**Average Stay Duration**: Average number of days stayed by a customer per booking[cite: 453, 526].

## 5. Revenue Analysis Dashboard
[cite_start]The final dashboard provides both high-level and granular insights, with interactive filters for Month-Year, City, Booking Platform, and Booking Status[cite: 434, 464, 518].

![Revenue Dashboard](# AtliQ Grands - Revenue Analysis and Business Intelligence Dashboard

## 1. Executive Summary
[cite_start]AtliQ Grands, a leading hotel chain in India, was experiencing a decline in market share and revenue performance due to increased competition and a lack of data-driven decision-making[cite: 500, 501]. [cite_start]This Business Intelligence project was initiated to identify revenue leakages, optimize occupancy, and enable strategic planning through a comprehensive Power BI dashboard[cite: 502, 503]. [cite_start]The goal is to track revenue sources and other critical performance indicators across all properties[cite: 426, 503].

## 2. Business Objective
[cite_start]The primary objective of this project was to implement a data intelligence solution to provide actionable insights into AtliQ Grands' business operations[cite: 505].

Specific goals included:
* [cite_start]Identifying key factors that influence revenue performance[cite: 507].
* [cite_start]Developing a KPI dashboard to track revenue sources and other relevant KPIs across various dimensions[cite: 427].
* [cite_start]Empowering the management team to make strategic, data-informed business decisions[cite: 428, 509].
* [cite_start]Increasing overall revenue and market share through enhanced performance tracking[cite: 510].

## 3. Technology Stack
* [cite_start]**Microsoft Power BI** [cite: 423, 496]
* [cite_start]**Power Query** (for data cleaning and transformation) [cite: 438, 496, 515]
* [cite_start]**Power Pivot** (for data modeling) [cite: 439, 496, 516]

## 4. Solution Approach

[cite_start]The project involved collecting, cleaning, and modeling data to create an interactive dashboard for tracking key metrics[cite: 430, 431, 520].

### Data Model
[cite_start]Five tables were used: 3 dimension tables (`dim_date`, `dim_hotels`, `dim_rooms`) and 2 fact tables (`fact_bookings`, `fact_aggregated_bookings`)[cite: 436]. [cite_start]Relationships were created in Power Pivot to build a robust data model for analysis[cite: 439, 516].
![Data modeling ](https://github.com/hiteshkumarh/AtliQ-Grands-Revenue-Analysis/blob/main/Screenshot%20data%20modeling.png)

### Key Performance Indicators (KPIs) Created
Several measures were created using DAX to calculate important business metrics:
* [cite_start]**Revenue**: Sum of revenue realized from the Bookings table[cite: 443].
* [cite_start]**Total Bookings**: Count of all booking IDs from the Bookings table[cite: 444, 523].
* [cite_start]**Average Rating**: Average of ratings given by customers[cite: 445, 527].
* [cite_start]**Total Capacity**: Sum of capacity from the Aggregated Bookings table[cite: 446].
* [cite_start]**Total Successful Bookings**: Sum of all successful bookings[cite: 447].
* [cite_start]**Occupancy Rate**: (Total successful bookings / Total capacity) %[cite: 450, 524].
* [cite_start]**Cancellation Rate**: (Total cancelled bookings / Total bookings) %[cite: 452, 525].
* [cite_start]**Average Stay Duration**: Average number of days stayed by a customer per booking[cite: 453, 526].

## 5. Revenue Analysis Dashboard
[cite_start]The final dashboard provides both high-level and granular insights, with interactive filters for Month-Year, City, Booking Platform, and Booking Status[cite: 434, 464, 518].

![Revenue Dashboard](https://github.com/hiteshkumarh/AtliQ-Grands-Revenue-Analysis/blob/main/Screenshot%20(55).png).


## 6. Business Insights & Outcomes
The dashboard generated several key insights that led to strategic actions:
* [cite_start]**Regional Performance**: Mumbai generates the highest revenue, while Delhi generates the least, indicating a need for targeted marketing strategies in Delhi[cite: 473, 537].
* [cite_start]**Occupancy Trends**: Occupancy rate is consistently higher during weekends across all properties[cite: 474, 538]. [cite_start]This insight can be leveraged to increase weekend revenue[cite: 475].
* [cite_start]**Booking Status**: About 75% of all bookings generate revenue (70% checked out, 5% no-shows)[cite: 476, 539]. [cite_start]The reasons for cancellations need to be analyzed to reduce them[cite: 477].
* [cite_start]**Delhi Anomaly**: Despite having the highest occupancy rate (over 60%), Delhi hotels generate the least revenue, suggesting potential issues with pricing strategy or product mix[cite: 482, 540].
* [cite_start]**Customer Metrics**: The average customer rating is between 3.4 and 3.8, and the average stay is 2.4 days[cite: 480, 541]. [cite_start]These metrics need to be evaluated against industry benchmarks[cite: 481].

## 7. Business Impact
[cite_start]The implementation of the dashboard enabled the Revenue Management team to make timely, data-driven decisions[cite: 543].
* [cite_start]**Revenue and market share improved by 20% within one month**[cite: 545].
* [cite_start]Management gained a holistic view of hotel performance, allowing them to monitor and respond to trends faster[cite: 546, 547].
* [cite_start]The project fostered a data-driven culture, helping the company make smarter decisions and supporting long-term business growth[cite: 487, 488, 552].

## 8. Project File Structure
* **/dasboard & PPT**: Contains the final Power BI dashboard file (`.pbix`) and the project presentation (`.pptx`).
* **/input files**: Contains all the raw CSV data files used for the analysis.
* `Revenue Analysis report.pdf`: A detailed report summarizing the project from objective to impact.


## 6. Business Insights & Outcomes
The dashboard generated several key insights that led to strategic actions:
* [cite_start]**Regional Performance**: Mumbai generates the highest revenue, while Delhi generates the least, indicating a need for targeted marketing strategies in Delhi[cite: 473, 537].
* [cite_start]**Occupancy Trends**: Occupancy rate is consistently higher during weekends across all properties[cite: 474, 538]. [cite_start]This insight can be leveraged to increase weekend revenue[cite: 475].
* [cite_start]**Booking Status**: About 75% of all bookings generate revenue (70% checked out, 5% no-shows)[cite: 476, 539]. [cite_start]The reasons for cancellations need to be analyzed to reduce them[cite: 477].
* [cite_start]**Delhi Anomaly**: Despite having the highest occupancy rate (over 60%), Delhi hotels generate the least revenue, suggesting potential issues with pricing strategy or product mix[cite: 482, 540].
* [cite_start]**Customer Metrics**: The average customer rating is between 3.4 and 3.8, and the average stay is 2.4 days[cite: 480, 541]. [cite_start]These metrics need to be evaluated against industry benchmarks[cite: 481].

## 7. Business Impact
[cite_start]The implementation of the dashboard enabled the Revenue Management team to make timely, data-driven decisions[cite: 543].
* [cite_start]**Revenue and market share improved by 20% within one month**[cite: 545].
* [cite_start]Management gained a holistic view of hotel performance, allowing them to monitor and respond to trends faster[cite: 546, 547].
* [cite_start]The project fostered a data-driven culture, helping the company make smarter decisions and supporting long-term business growth[cite: 487, 488, 552].

## 8. Project File Structure
* **/dasboard & PPT**: Contains the final Power BI dashboard file (`.pbix`) and the project presentation (`.pptx`).
* **/input files**: Contains all the raw CSV data files used for the analysis.
* `Revenue Analysis report.pdf`: A detailed report summarizing the project from objective to impact.
