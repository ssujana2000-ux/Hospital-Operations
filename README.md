# Hospital-Operations

Power BI dashboard analyzing Hospital operations and workforce management.</br>
https://www.kaggle.com/datasets/jaderz/hospital-beds-management

# 📁 Project Structure

data/</br>
patients.csv</br>
services_weekly.csv</br>
staff.csv</br>
staff_schedule.csv

dashboard/</br>
Hospital Operations Dashboard.pbix

README.md

# 📊 Dashboard Preview
<img width="1117" height="625" alt="image" src="https://github.com/user-attachments/assets/3aca6309-4f5b-4dbc-bbec-f6ff2eeef8cf" />


# 📌 Project Overview

This Power BI project analyzes hospital operations including weekly patient admissions, bed availability, service-level satisfaction, staff availability across services to optimize resource allocation and improve patient care operations.

The dashboard is designed to help stakeholders identify:

•	Capacity bottlenecks</br>
•	Staffing pressure points</br>
•	Service-level performance gaps</br>
•	Operational risks during high-demand events

# Data Modelling

•	Patients, staff and staff schedules table were categorized as dimension tables while services_weekly was a transactional table capturing weekly transactional data</br>
•	To avoid altering the structure of tables, A separate dimension table Service was created and joined to other tables using 1-many relationships.</br>
•	All the staff attributes present in the staff table were also present in staff_schedule, the latter was prioritised in this analysis.

# 📈 Core Analyses

•	Average length of stay by service</br>
•	Bed capacity vs patient demand</br>
•	Admission, refusal, and bed utilization rates</br>
•	Staff-to-patient ratio by event</br>
•	Patient age distribution</br>
•	Weekly trends in admissions, refusals, and staff presence</br>
•	Top 3 and Bottom 3 service performance using dynamic ranking

# 🧠 Key Insights

•	Emergency services show the highest bed utilization and refusal rates</br>
•	Staff-to-patient ratios vary significantly during disruptive events</br>
•	Higher staffing availability generally aligns with improved patient satisfaction</br>
•	Certain services consistently rank among top or bottom performers, enabling targeted interventions.</br>

# Dashboard Summary

This project demonstrates:</br>
•	Business-driven KPI design</br>
•	Data modeling best practices</br>
•	Analytical thinking</br>
•	Interactive dashboard development</br>
•	Real-world healthcare analytics use cases



