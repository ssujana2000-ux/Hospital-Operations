# Hospital-Operations
Power BI dashboard analyzing Hospital operations and workforce management.
https://www.kaggle.com/datasets/jaderz/hospital-beds-management

📁 Project Structure
data/
patients.csv
services_weekly.csv
staff.csv
staff_schedule.csv

dashboard/
Hospital Operations Dashboard.pbix

README.md

📊 Dashboard Preview
<img width="1376" height="768" alt="image" src="https://github.com/user-attachments/assets/24014e50-d22c-4e2f-938a-5e4229690aff" />

📌 Project Overview
This Power BI project analyzes hospital operations including weekly patient admissions, bed availability, service-level satisfaction, staff availability across services to optimize resource allocation and improve patient care operations.
The dashboard is designed to help stakeholders identify:
•	Capacity bottlenecks
•	Staffing pressure points
•	Service-level performance gaps
•	Operational risks during high-demand events

Data Modelling
•	Patients, staff and staff schedules table were categorized as dimension tables while services_weekly was a transactional table capturing weekly transactional data
•	To avoid altering the structure of tables, A separate dimension table Service was created and joined to other tables using 1-many relationships.
•	All the staff attributes present in the staff table were also present in staff_schedule, the latter was prioritised in this analysis.

📈 Core Analyses
•	Average length of stay by service
•	Bed capacity vs patient demand
•	Admission, refusal, and bed utilization rates
•	Staff-to-patient ratio by event
•	Patient age distribution
•	Weekly trends in admissions, refusals, and staff presence
•	Top 3 and Bottom 3 service performance using dynamic ranking

🧠 Key Insights
•	Emergency services show the highest bed utilization and refusal rates
•	Staff-to-patient ratios vary significantly during disruptive events
•	Higher staffing availability generally aligns with improved patient satisfaction
•	Certain services consistently rank among top or bottom performers, enabling targeted interventions.

Dashboard Summary
This project demonstrates:
•	Business-driven KPI design
•	Data modeling best practices
•	Analytical thinking
•	Interactive dashboard development
•	Real-world healthcare analytics use cases



