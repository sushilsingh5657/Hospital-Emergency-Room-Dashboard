# Excel Project: Hospital-Emergency-Room-Dashboard
This Excel dashboard provides a holistic view of emergency room operations and patient flow throughout the year. It consolidates critical healthcare KPIs in a visually intuitive format, empowering hospital administrators and decision-makers to analyze and improve service delivery.
# 📊 Key Metrics Covered:
•	Patient Overview: Tracks the total number of patients (e.g., 513 in January) to monitor ER traffic trends and prepare staffing and resource planning accordingly.

•	Average Wait Time: Measures the time patients spend before being attended by a healthcare professional, helping assess the efficiency of hospital operations.

•	Patient Satisfaction Score: Captures patient feedback on their ER experience, giving a direct insight into service quality and areas for improvement.
# 🛏️ Admission Analysis:
•	Displays a split between Admitted and Not Admitted patients, offering visibility into the conversion rate of ER visits into inpatient cases. This helps in capacity planning and resource allocation.
# 👥 Patient Demographics:
•	Age-wise Distribution: Shows patient count across various age groups (0–79 years), identifying age-related trends and potential health focus areas.

•	Gender-wise Analysis: Highlights the male-female patient ratio, which supports targeted health programs and resource planning.
# ⏱️ Attendance Status:
•	Compares the number of on-time vs delayed patient attendances to track operational punctuality and identify bottlenecks in service delivery.
# 🏥 Departmental Referrals:
•	Displays how many patients are referred to various departments such as General Practice, Orthopedics, Cardiology, Neurology, etc., helping assess departmental load and inter-departmental coordination.
# 📅 Time Navigation:
•	Monthly buttons (Jan–Dec) allow users to interactively filter the data by month while still maintaining a cumulative yearly overview. This enhances usability and supports both trend analysis and detailed monthly reviews.

<img width="868" alt="Excel Dashboard1" src="https://github.com/user-attachments/assets/e8835cc7-1d89-49ca-a80f-d5be301f67f5" />

# 🎯 Objective of the Dashboard
The objective of this dashboard is to provide a comprehensive and real-time overview of key metrics related to hospital emergency room operations. It helps stakeholders monitor:

•	Patient Volume: Total number of patients per month.

•	Operational Efficiency: Average wait times and patient attend status (on-time vs. delayed).

•	Patient Experience: Satisfaction scores and admission rates.

•	Demographics: Patient age group distribution and gender analysis.

•	Departmental Insights: Patient referrals by medical departments.

This dashboard enables healthcare administrators to identify performance gaps, allocate resources efficiently, and improve patient care delivery.

# ⚙️ Process & Steps Involved:
# 1. Requirement Gathering and Planning
•	Identified KPIs: number of patients, wait time, satisfaction score, admission status, gender & age distribution, departmental referrals, and attend status.

•	Defined the purpose: visualize hospital emergency room performance for better insights and decisions.

•	Outlined user expectations: monthly-wise analysis with yearly context.
________________________________________
# 2. Data Collection and Preparation
•	Collected raw data from hospital records or sample datasets.

•	Cleaned data:

o	Removed duplicates and blanks.

o	Standardized date formats.

o	Handled missing values.

•	Structured tables for:

o	Patient demographics (age, gender).

o	Visit details (wait time, attend status).

o	Admission and referral status.

# 3. Pivot Tables & Charts:
•	Used Pivot Tables to summarize categorical data (e.g., admission status, age groups).

•	Created bar charts for:

o	Age group distribution

o	Department referrals

•	Created pie/donut charts for:

o	Gender analysis

o	Attendance status
# 4. Data Analysis
•	Used Excel formulas like:

o	COUNTIFS, SUMIFS, AVERAGEIFS for KPI calculations.

o	IF, VLOOKUP, INDEX-MATCH for conditional logic.

o	TEXT, DATE, LEFT/RIGHT/MID for formatting and transformations.
________________________________________
# 5. Dashboard Design
•	Created layout with clear sections:

o	KPIs at the top.

o	Charts for patient status, gender, age group.

o	Slicers for month and year filtering.

o	Admission and department breakdowns.


•	Applied consistent color themes (e.g., blue & orange) for readability and visual appeal.
________________________________________
# 6. Chart Creation
•	Built visuals using:

o	Bar Charts: Patient by age group, department referral.

o	Pie/Donut Charts: Gender and attend status.

o	Line Charts/Sparklines: Trend indicators for KPIs.

•	Used dynamic ranges and named ranges for responsiveness to slicers.
________________________________________
# 7. Interactivity with Slicers and Filters
•	Added Month and Year Slicers to allow real-time filtering of visuals.

•	Linked slicers with PivotTables to update all metrics dynamically.
________________________________________
# 8. Testing and Validation
•	Validated metrics against source data for accuracy.

•	Checked slicer responsiveness and interactivity.

•	Ensured all visuals update correctly as filters change.


________________________________________
# 🛠️ Tools & Features Used:
•	Microsoft Excel

•	Pivot Tables & Pivot Charts

•	Slicers for interactivity

•	Conditional Formatting

•	Formulas like COUNTIF(), AVERAGE(), SUMIF(), IF()

•	Chart Tools (Bar, Pie, Donut)

•	Icons and Shapes for UI enhancement

# Purpose and Usage

The dashboard is designed to:

•	Improve transparency and decision-making in ER operations.

•	Help optimize patient flow and resource management.

•	Identify service bottlenecks and demographic trends.

•	Track year-over-year performance with actionable insights.

<img width="861" alt="Excel Dashboard2" src="https://github.com/user-attachments/assets/7daa08e0-6bba-4470-a75f-55f5c58d0bd0" />

# Dashboard 2: Daily Volume Trend

Focus: Shows how many instances (likely customers, tasks, or visits) occurred daily.

•	Use: Helps identify busy days (like 5-Jan, 14-Jan, 28-Jan with values 22, 25, and 20) and low-activity days (e.g., 19-Jan with a value of 10).

•	Insight: Perfect for workload analysis or capacity planning.

<img width="877" alt="Excel Dashboard3" src="https://github.com/user-attachments/assets/ca322208-8479-4bf1-bab6-78604911052f" />

# Dashboard 3: Wait Time Analysis

Focus: Displays average wait times for each day.

•	Use: Detects days where wait times were unusually high (e.g., 8-Jan: 43.52 mins, 19-Jan: 41.60 mins), suggesting possible inefficiencies.

•	Insight: These peaks could relate to staff shortages, high traffic, or technical issues.

<img width="864" alt="Excel Dashboard4" src="https://github.com/user-attachments/assets/f67554d2-24c9-40fd-9c54-ba52c1ceac45" />

# Dashboard 4: Satisfaction Trend

Focus: Tracks daily customer satisfaction scores.

•	Use: Indicates satisfaction dips on certain days (e.g., 31-Jan: 1.40; 9-Jan: 3.00), which can be cross-referenced with busy days or long wait times.

•	Insight: A sharp drop in satisfaction often coincides with high volume or wait times—valuable for identifying root causes.

# Summary of Insights
The dashboards reveal a strong connection between daily customer volume, wait time, and satisfaction levels. High customer volume often leads to longer wait times, which negatively impacts satisfaction. However, efficient handling on high-volume days can still maintain high satisfaction scores, as seen on specific dates. Notably, low volume doesn’t always ensure better service, indicating possible inefficiencies. Overall, maintaining consistent operational performance and balancing resources according to traffic patterns are key to improving both wait times and customer satisfaction.



