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
