**Alzheimer’s Disease at a Glance: Neuroimaging Analytics**

A Power BI-Based Brain Scan Visualization Dashboard
________________________________________
**Project Overview**

**Objective:**

To build a visual diagnostic framework using brain scan metrics (entropy, clarity, brightness) to assess Alzheimer's Disease severity across four stages: Non-Demented, Very Mild, Mild, and Moderate Dementia.
________________________________________
**Key Findings**

•	Moderate dementia scans showed the lowest clarity and highest disorder.
•	Entropy levels were surprisingly similar between healthy and early-stage patients.
•	Central brightness sharply increased with severity, suggesting its importance as a marker.
•	Composite metrics combining entropy, edge density, and brightness provided the most diagnostic insight.
________________________________________
**Dataset Summary**

**Dashboard Highlights:**

•	KPIs for disease progression, scan disorder, radiance, brightness, and centre clarity
•	Image comparison of healthy vs. diseased brain scans
•	Entropy and pixel intensity distributions by condition
•	Composite Severity formula derived from normalized imaging indicators

**Data Source:**

MRI imaging statistics from open Alzheimer’s datasets (OASIS, ADNI).
________________________________________
**Methodology**

**Tools Used:**

•	Power BI Desktop
•	DAX for metric calculations (e.g., Composite Severity, Entropy Index)
•	Image gallery slicers
•	Bar, donut, and card visualizations

**Approach:**

•	Created Severity Score via SWITCH function
•	Applied filters to isolate metrics by disease stage
•	Combined radiometric indicators into a single diagnostic score
________________________________________
**Recommendations**

•	Use Composite Severity to train AI models for early detection.
•	Focus research on centre brightness and clarity as reliable disease indicators.
•	Add demographic data (age, gender) for longitudinal analysis in future versions.
________________________________________
**How to Use This Project**

1.	Load the .pbix file into Power BI Desktop.
2.	Review disease progression and entropy charts for stage-by-stage comparison.
3.	Interact with slicers to focus on specific cognitive conditions.
4.	Analyse how clarity and brightness evolve across scans.
________________________________________
**About**

This project demonstrates how visual analytics in Power BI can support healthcare diagnostics. It merges neuroimage data with interactive visuals to help clinicians and researchers identify cognitive decline patterns more clearly.

**Author**: Williams Obinna

**Email**: obinnawilliams3@gmail.com

![Alzheimer's Disease Dashboard](https://github.com/user-attachments/assets/6ae877a6-5100-4c58-8d7e-f596e32b1233)


