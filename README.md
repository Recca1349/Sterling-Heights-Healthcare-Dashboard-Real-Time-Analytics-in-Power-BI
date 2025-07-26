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

## Data Analysis and Insight
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


### **2. Area Chart – Patient Visit Trends**
**What it shows:** Monthly patient visit counts from January to December, split into Admitted and Not Admitted categories.

**Insight:**
July recorded the highest number of total visits: 122, made up of 78 not admitted and 44 admitted patients. In contrast, January had 94 total visits, with 38 admitted and 56 not admitted. This reflects a 30% increase in total visits from January to July, driven mostly by a rise in non-admitted cases.

**Use:** This chart helps hospital administrators track patient volumes over time, evaluate seasonal trends, and make proactive staffing or resource allocation decisions based on admission patterns.

### **3. Combination of Matrix, Clustered Column Chart and Stacked Bar Chart – Patient Visit by Day and Time**
This area chart displays high-traffic periods by combining days of the week with visit times. It helps reveal peak hours to inform staffing and scheduling decisions.

### **4. Donut Chart – Patient Visit by Gender**
**What it shows:** Gender distribution of hospital visits.

**Insight:**
The majority of hospital visits were made by male patients, accounting for 51.42% of the total, with 617 visits. Female patients represented 48.58%, with 583 visits. While the margin is narrow, it indicates a slight male predominance in hospital utilization during the period.

**Use:** This insight can inform gender-focused healthcare outreach, service planning, and support programs. It may also guide departments like men's health or preventive care initiatives based on utilization patterns.

### **5. Bar Chart – Patient Visit by Treatment Category**
**What it shows:** The number of patient visits grouped by treatment type, allowing comparison across different medical service areas.

**Insight:**
Radiology recorded the highest number of visits (239), followed by Orthopedics (133) and Dermatology (129). On the other end, Pediatrics (113) and Dentistry (109) had the lowest patient volumes, indicating relatively lower demand for these services during the analyzed period.

**Use:** This visualization helps hospital management identify high-demand departments for potential investment or expansion and evaluate underused services for restructuring, promotion, or resource reallocation. It supports data-driven service planning and operational optimization.

### **6. Line Chart – Daily Doctor Trend**
**What it shows:** The number of doctors on duty per day over a 30-day period, illustrating fluctuations in staff availability.

**Insight:**
Doctor availability peaked on Day 12 with 34 doctors, but significantly dropped to 18 doctors on Day 22, likely due to holidays, off-duty shifts, or scheduling constraints. This drop could impact patient care quality and waiting times if not proactively managed.

**Use:** This chart is vital for workforce planning, helping management anticipate staffing needs, balance workloads, and prevent service disruptions during low-staff days, especially when aligned with patient volume trends.
