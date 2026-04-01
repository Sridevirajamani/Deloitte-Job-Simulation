# Deloitte Job Simulation – Forensic Technology

This repository contains my deliverables from Deloitte’s Forensic Technology Job Simulation.  
The simulation focused on analyzing **gender pay equality** and **factory downtime telemetry data**, using Excel and Tableau to generate client-ready insights.

---

## Task 1: Telemetry Data Analysis (Tableau)
- Imported JSON telemetry data into Tableau, ensuring schema levels were correctly mapped.
- Created a calculated field **"Unhealthy"** to represent 10 minutes of potential downtime per unhealthy status.
- Built bar charts:
  - **Down Time per Factory**
  - **Down Time per Device Type**
- Combined charts into an interactive dashboard:
  - Selecting a factory filters device type downtime.
- Identified the factory with the highest downtime and captured a screenshot of the dashboard.

**Deliverable:**  
- `Task1_Deloitte_Tableau_Dashboard.png`

---

## Task 2: Gender Pay Equality Classification (Excel)
- Processed employee compensation data from `Equality Table.xlsx`.
- Added a new column **Equality Class** to categorize scores:
  - **Fair** → Score between -10 and +10  
  - **Unfair** → Score between -20 and -11 OR 11 and 20  
  - **Highly Discriminative** → Score less than -20 OR greater than 20
- Formula used:
  ```excel
  =IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))

---

## Key Skills Demonstrated
- Data visualization with Tableau
- Data classification and analysis with Excel
- Problem-solving and consulting-style presentation
- Translating raw data into actionable business insights

---

## Author
**Sri Devi R**
B.Sc. Data Science & Analytics Graduate
Skilled in SQL, Python, Excel, Tableau, and Power BI


  
