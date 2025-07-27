# Healthcare Operations & Patient Experience Dashboard (Power BI)

![hospital image2](https://github.com/user-attachments/assets/034d44eb-9a9a-468e-b8e9-37059d226f27)

**Disclaimer**⚠️: All datasets, slides and reports do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual mention. All info are dummy and design to demonstrate my capabilities of using PowerBI to perform advance analysis on healthcare dataset

## Description
This is designed and developed comprehensive Power BI dashboard for Sterling Heights Hospital, a mid-sized healthcare facility seeking to improve operational oversight and patient-centered care. The dashboard provides real-time insights into patient visit patterns, treatment categories, doctor availability, and satisfaction metrics. By transforming raw hospital data into actionable visuals, this solution supports informed decision-making, optimizes staff allocation, and enhances visibility into key performance indicators across departments. The project highlights my ability to apply data analytics and visualization techniques to address real-world challenges in the healthcare sector.

## Business Introduction
Sterling Heights Hospital is a mid-sized, modern healthcare facility committed to delivering high-quality, patient-centered care. Serving a diverse community, the hospital offers a wide range of medical services across specialties such as cardiology, pediatrics, orthopedics, internal medicine, and emergency care. Known for its dedicated team of healthcare professionals and its emphasis on compassionate treatment, Sterling Heights strives to enhance patient outcomes through continuous innovation, evidence-based practices, and the integration of advanced medical technologies. The hospital also focuses on operational excellence, aiming to reduce wait times, streamline workflows, and provide a seamless care experience for every patient. Sterling Heights Hospital’s mission is to promote health and healing in a safe, welcoming environment—ensuring that every patient receives the highest standard of care from diagnosis to recovery.

## Problem Statement
Sterling Heights Hospital was facing significant operational inefficiencies that affected both staff performance and patient satisfaction. Key challenges included prolonged patient wait times, uneven doctor workloads, and a lack of real-time visibility into patient flow and treatment trends. These issues hindered the hospital's ability to allocate resources effectively, monitor service performance, and make timely, data-driven decisions—ultimately impacting the quality of care delivered to patients.

## Aim of the Project
- To provide Sterling Heights Hospital with a centralized and interactive Power BI dashboard for operational monitoring.
- To visualize patient visit trends, including admitted vs non-admitted cases, gender distribution, and peak visit times.
- To analyze doctor availability by day, gender, and specialty for improved workforce planning.
- To track treatment categories and highlight both common and rare procedures.
- To correlate patient wait times with satisfaction scores for quality improvement.
- To equip hospital management with real-time data to support proactive decision-making.
- To enhance overall visibility into hospital performance through intuitive, data-driven reporting.
- To transform raw healthcare data into actionable insights that improve service delivery and resource allocation.

## Methodologies Used
- **Business Understanding:** Defined the project objective to analyze Sterling Heights Hospital’s patient flow, treatment trends, and doctor utilization in order to uncover operational inefficiencies, improve patient satisfaction, and support data-driven healthcare decisions.
- **Data Collection & Cleaning:** Gathered patient visit records, doctor schedules, treatment logs, and satisfaction scores. Cleaned and transformed data using Microsoft Excel for consistency and accuracy.
- **Data Understanding:** Explored and reviewed hospital datasets, including patient visit logs, treatment records, admission status, doctor rosters, and satisfaction surveys to understand key operational and service-related variables.
- **Data Modeling in Power BI:** Established relationships between tables (e.g., patient dimension table, doctor table, treatments table, location table, calender table, and Sterling Heights fact table) using a star schema. Created a logical data model to support efficient querying and slicing.
- **DAX Measures & Calculations:** Created custom DAX formulas to calculate KPIs such as patient wait time, doctor availability, visit frequency, and average satisfaction scores.
- **Dashboard Design & Visualization:** Built an interactive Power BI dashboard with visual elements such as:
   - Heatmaps (to show peak hours)
   - Bar and column charts (for category and gender analysis)
   - Scatter plots (for wait time vs satisfaction)
   - Line charts (for trends)
   - Filters and slicers (for easy exploration)
- **KPI Development:** Defined key performance indicators aligned with hospital goals, such as average wait time, patient satisfaction score, and doctor workload distribution.
- **Iterative Review & Enhancement:** Refined visuals and measures through feedback loops to ensure clarity, usability, and relevance to hospital management.
- **Performance Optimization:** Improved report responsiveness by optimizing data size, using calculated columns/measures efficiently, and reducing unnecessary visuals.
- **Documentation & Knowledge Sharing:** Documented data sources, definitions, and usage guides to support dashboard adoption by non-technical users.

## Data Modeling
The data model for this project was designed using a star schema to support efficient analysis and reporting in Power BI. A central fact table—containing patient visit records such as visit time, admission status, treatment type, and satisfaction scores—was connected to five dimension tables: Calendar (for time-based trend analysis), Doctor (ID, gender, specialty, and availability), Treatment (procedure categories), Patient Demographics (age group and gender), and Location (representing hospital facilities or departments where services were rendered). Relationships were established using unique identifiers like patient ID, doctor ID, location ID, treatment ID and date. The model was optimized with single-directional relationships, minimized calculated columns, and well-structured DAX measures. This clean, scalable structure enabled dynamic filtering, drill-through capabilities, and real-time insights into operational and service delivery performance across the hospital.

<img width="1920" height="957" alt="Sterling moel shot" src="https://github.com/user-attachments/assets/f172f207-088e-4723-a22f-92d421d24092" />


## Visualization
- KPIs
- Stacked Column Chart 
- Visits by Day and Time
- Matrix 
- Donut Chart 
- Visits by Treatment Category
- Bar Chart 
- Area Chart 
- Scatter Plot 
- Table Visual

## Data Analysis
## **1. Key Performance Indicators**
**What it shows:** Key Metrics such as:
Number of Visits: 1,200, Number of Doctors: 50, Number of Patients: 294, Avgerage Wait Time: 92.0 mins, Admission Rate: 41.25%, Total Profit: $1.48 million, Average Age: 46.70, Doctor to Patient ratio: 0.17, Average Rating: 3.02, and Admission Rate: 41.25% 

**Insight:**
   - The average wait time of 92 minutes is relatively high and may be contributing to the moderate satisfaction rating of 3.02, signaling a need to improve service delivery speed.

   - With 294 patients and 50 doctors, the doctor-to-patient ratio of 0.17 suggests a potential overload on staff or underutilization, depending on shift distributions.

   - The admission rate of 41.25% indicates that nearly 6 out of every 10 patients are treated without being admitted, highlighting the hospital’s strong outpatient engagement.

   - A total profit of $1.48 million reflects financial viability, but it must be balanced with patient experience metrics to ensure sustainability.

   - The average patient age of 46.7 years may help prioritize services for middle-aged or chronic care populations.

**Use:** The KPIs help with the following:
   - Enables hospital leadership to monitor overall performance at a glance and identify critical areas for improvement.

   - Supports operational reviews, budget planning, staffing decisions, and patient service strategy.

   - Helps stakeholders align clinical and financial performance by viewing patient volume, profitability, and satisfaction in a unified dashboard.

   - Useful for setting benchmarks and tracking the impact of process improvements over time.

<img width="1033" height="132" alt="sterling kpi1 shot" src="https://github.com/user-attachments/assets/15730d60-893b-4c2d-985d-2568e0bd98d9" />


<img width="1035" height="128" alt="sterling kpi2 shot" src="https://github.com/user-attachments/assets/e5ea6a44-2f68-4444-af00-3058d02ea20c" />


### **2. Area Chart – Patient Visit Trends**
**What it shows:** Monthly patient visit counts from January to December, split into Admitted and Not Admitted categories.

**Insight:**
July recorded the highest number of total visits: 122, made up of 78 not admitted and 44 admitted patients. In contrast, January had 94 total visits, with 38 admitted and 56 not admitted. This reflects a 30% increase in total visits from January to July, driven mostly by a rise in non-admitted cases.

**Use:** This chart helps hospital administrators track patient volumes over time, evaluate seasonal trends, and make proactive staffing or resource allocation decisions based on admission patterns.

<img width="652" height="237" alt="sterling Patient visit shot" src="https://github.com/user-attachments/assets/47176c15-e069-4c88-91cc-8515dbc2d394" />

### **3. Combination of Matrix, Clustered Column Chart and Stacked Bar Chart – Patient Visit by Day and Time**
This area chart displays high-traffic periods by combining days of the week with visit times. It helps reveal peak hours to inform staffing and scheduling decisions.

<img width="717" height="307" alt="sterling Patient visit by day shot" src="https://github.com/user-attachments/assets/0466ca79-5edb-4172-80da-2ba6b8bc8994" />

### **4. Donut Chart – Patient Visit by Gender**
**What it shows:** Gender distribution of hospital visits.

**Insight:**
The majority of hospital visits were made by male patients, accounting for 51.42% of the total, with 617 visits. Female patients represented 48.58%, with 583 visits. While the margin is narrow, it indicates a slight male predominance in hospital utilization during the period.

**Use:** This insight can inform gender-focused healthcare outreach, service planning, and support programs. It may also guide departments like men's health or preventive care initiatives based on utilization patterns.

<img width="497" height="238" alt="sterling Patient visit by gender shot" src="https://github.com/user-attachments/assets/dba76c3b-30e7-4110-981d-45e34a609a56" />

### **5. Bar Chart – Patient Visit by Treatment Category**
**What it shows:** The number of patient visits grouped by treatment type, allowing comparison across different medical service areas.

**Insight:**
Radiology recorded the highest number of visits (239), followed by Orthopedics (133) and Dermatology (129). On the other end, Pediatrics (113) and Dentistry (109) had the lowest patient volumes, indicating relatively lower demand for these services during the analyzed period.

**Use:** This visualization helps hospital management identify high-demand departments for potential investment or expansion and evaluate underused services for restructuring, promotion, or resource reallocation. It supports data-driven service planning and operational optimization.

<img width="432" height="306" alt="sterling Patient visit by treat shot" src="https://github.com/user-attachments/assets/6b10b308-46f0-41d4-8aa2-39e4fb1db431" />

### **6. Line Chart – Daily Doctor Trend**
**What it shows:** The number of doctors on duty per day over a 30-day period, illustrating fluctuations in staff availability.

**Insight:**
Doctor availability peaked on Day 12 with 34 doctors, but significantly dropped to 18 doctors on Day 22, likely due to holidays, off-duty shifts, or scheduling constraints. This drop could impact patient care quality and waiting times if not proactively managed.

**Use:** This chart is vital for workforce planning, helping management anticipate staffing needs, balance workloads, and prevent service disruptions during low-staff days, especially when aligned with patient volume trends.

<img width="652" height="241" alt="sterling doc trend shot" src="https://github.com/user-attachments/assets/9ca9f357-4e63-4823-80d2-3cd4b461e600" />

### **7. Bar Chart – Doctors by Specialty**
**What it shows:** The distribution of doctors across various departments, highlighting how medical staff are spread among specialties.

**Insight:**
Dermatology, Orthopedics, and Ophthalmology have the highest number of doctors, suggesting they are better staffed to meet demand. In contrast, Dentistry and Surgery have the fewest doctors, which may indicate under-resourcing or less demand in those departments.

**Use:** This chart supports strategic hiring decisions and helps hospital administrators ensure balanced capacity across departments, avoiding both understaffing and redundancy in specialty areas.

<img width="717" height="305" alt="sterling doc spec shot" src="https://github.com/user-attachments/assets/def6cd49-9f59-4e85-acdb-e0f966e57ea2" />


### **8. Donut Chart – Doctors by Gender**
**What it shows:** The gender distribution of doctors across the hospital, giving a high-level view of staff diversity.

**Insight:**
The medical staff is evenly split, with 25 female doctors (50%) and 25 male doctors (50%). This indicates gender parity in staffing at the hospital—a strong indicator of equitable hiring practices.

**Use:** This chart promotes awareness of diversity and inclusion in the workforce. It supports ongoing efforts to maintain balance across roles and departments, which can positively impact patient trust, team dynamics, and organizational culture.

<img width="501" height="237" alt="sterling doc gender shot" src="https://github.com/user-attachments/assets/9b66d290-61d7-4232-8978-820e65349e60" />

### **9. Scatter Plot – Avg. Wait Time vs. Avg. Satisfaction by Treatment**
**What it shows:** It illustrates the correlation between average wait time and average patient satisfaction score for each treatment category. Each point represents a treatment, showing how wait duration may influence the patient's experience.

**Insight:**
The chart reveals a weak negative correlation between wait time and satisfaction score — as wait times increase, satisfaction scores tend to decrease, but not consistently or strongly.

For instance:
   - X-Ray: 81.04 mins, Satisfaction 2.97
   - MRI Scan: 84.90 mins, Satisfaction 2.84
   - General Checkup: 88.34 mins, Satisfaction 2.92
   - Dental Cleaning: 89.54 mins, Satisfaction 3.08

These values suggest that while longer waits may be associated with slightly lower satisfaction, the correlation is not strong — indicating that other factors (such as staff attitude, clarity of communication, or treatment quality) also significantly impact satisfaction.

**Use:** 
This visualization helps the hospital:
   - Identify departments with both high wait times and low satisfaction for targeted workflow optimization.
   - Understand that reducing wait time alone may not fully improve satisfaction.
   - Prioritize patient experience initiatives in areas where satisfaction is lagging despite efficient wait times.

<img width="435" height="307" alt="sterling wait time shot" src="https://github.com/user-attachments/assets/19c5b189-099e-4613-b855-c3d04f32ad11" />

### **10. Table – Patient Visit Register**
**What it shows:** Detailed records of each visit: Patient ID, Year, Time, Admission Status, Treatment, Location, etc.

**Use:** Allows detailed review, auditing, and data validation. Supports deep dives into patterns or anomalies.

<img width="1176" height="760" alt="patient register shot" src="https://github.com/user-attachments/assets/6a5428eb-d808-4b73-ae75-41c3d7e3567e" />


## Dashboard Review

### **1. General Overview Dashboard**
This dashboard provides a high-level summary of the hospital’s operational and clinical performance. It highlights essential KPIs such as total visits, admission rates, wait times, satisfaction scores, and profitability. Visuals include visit trends over time, traffic patterns by day and hour, gender distribution, and visits by treatment category—offering actionable insight into patient flow, departmental demand, and service efficiency.

<img width="1328" height="753" alt="Sterling Hospital dash1" src="https://github.com/user-attachments/assets/164587cb-fb81-461a-8a1f-49246ba05a5c" />


### **2. Doctor Analysis Dashboard**
Focused on medical personnel, this dashboard visualizes doctor availability, specialty distribution, and gender diversity. It includes a daily trend of doctors on duty, doctor count by specialty, and a gender breakdown, helping management evaluate staffing levels, ensure balanced coverage across departments, and support diversity in hiring. A scatter plot compares patient wait time with satisfaction scores to assess performance at the departmental level.

<img width="1330" height="757" alt="Sterling Hospital dash2" src="https://github.com/user-attachments/assets/376f4ba7-4fcc-4624-b197-7ee38f47aad8" />


### **3. Patient Register Dashboard**
This dashboard presents a detailed table of patient-level data, capturing key attributes such as patient name, patient ID, wait time, treatment type, treatment typr, and satisfaction score, etc. It serves as a data validation and audit tool, allowing for granular exploration of patient history and enabling root-cause analysis of patterns or anomalies.

<img width="1331" height="757" alt="Sterling Hospital dash3" src="https://github.com/user-attachments/assets/2f39aac0-924c-4b07-8f01-9c9554789de5" />


## Insights and Recommendations
**1. Reduce Average Wait Time**

**Insight:** Current average wait time is 92 minutes, contributing to moderate satisfaction (3.02).

**Recommendation:**
   - Redesign appointment scheduling to reduce bottlenecks during peak hours.
   - Implement a fast-track system for low-complexity cases.
   - Explore digital check-ins or queue management tools.

**2. Optimize Doctor Allocation**

**Insight:** Doctor availability fluctuated, dropping to 18 on Day 22.

**Recommendation:**
  - Create a dynamic scheduling system to ensure sufficient coverage during high-traffic days.
  - Use patient visit trends to align staffing with demand by department and time.

**3. Improve Patient Satisfaction Beyond Wait Times**

**Insight:** Weak negative correlation between wait time and satisfaction shows other factors also affect patient experience.

**Recommendation:**
   - Train frontline staff in communication and empathy.
   - Improve in-visit experience (e.g., updates during wait, more comfortable waiting areas).
   - Introduce feedback kiosks to capture real-time patient sentiment.

**4. Leverage High-Demand Departments**

**Insight:** Radiology, Orthopedics, and Dermatology had the highest visits.

**Recommendation:**
   - Invest in expanding services and staff in these high-demand areas.
   - Bundle popular services with underused ones to balance traffic.

**5. Review and Promote Underutilized Services**

**Insight:** Pediatrics and Dentistry had the lowest visits.

**Recommendation:**
   - Conduct outreach campaigns targeting families and young adults.
   - Offer promotional health packages to raise awareness.

**6. Strengthen Outpatient Services**

**Insight:** 59% of visits are non-admitted, highlighting strong outpatient usage.

**Recommendation:**
   - Expand outpatient clinic hours.
   - Introduce online consultations or follow-ups to reduce physical congestion.

**7. Enhance Data Quality and Reporting**

**Recommendation:**
   - Maintain and routinely audit the patient register dashboard.
   - Use it to trace anomalies, identify repeat visitors, and improve case tracking.
