# Analyzing GASTech Building Operations Data

## 📌 Project Overview
This project explores and analyzes the GASTech Building Operations Data from the VAST Challenge 2016 (Mini-Challenge 2). By leveraging visual analytics and data-driven insights, we aim to detect patterns in employee movements, environmental conditions, and operational anomalies within the building.

Our analysis utilizes proximity sensor data, HVAC system readings, Hazium levels, and employee movement logs to detect security threats, optimize energy efficiency, and improve operational workflows.

## 🎯 Objectives
+ Analyze Employee Movements 🏢: Examine prox card data to determine typical movement patterns.  
+ Investigate Building Operations 🔥: Explore temperature, air supply rates, and electricity demand trends.  
+ Detect Anomalies 🚨: Identify unusual activities such as energy spikes, hazardous gas concentrations, and security breaches.  
+ Correlate Employee Behavior & Building Conditions 📊: Understand how movements impact HVAC, lighting, and security.

## 🗂 Dataset Description
We analyzed multiple datasets related to GASTech's building operations, including:

+ Building Layout 📍: Physical structure and proximity zones.  
+ Employee List 👥: Roles, departments, and office assignments.  
+ Proximity Sensor Data 🔄: Employee movements tracked via prox cards.  
+ HVAC Sensor Data ❄️: Heating, cooling, and air circulation information.  
+ Hazium Sensor Data ☣️: Potential hazardous gas levels within the facility.

## 🔍 Key Findings
### 1️⃣ Employee Movement Analysis
+ Employees follow standard work schedules: 8 AM - 5 PM (Weekdays), with Facilities & IT working 4 PM - Midnight and Midnight - 8 AM.  
+ Prox card inconsistencies: Employees like Marin Onda, Walton Reynoso, and Yuko Finney frequently leave their cards in their offices.  
+ Suspicious movement: Employees Mat Bramar and Orhan Strum used their prox cards on June 11 (weekend), just before a Hazium gas outbreak.
🖼 Suggested Image:
✅ Heatmap of Employee Movements Across Different Floors (Highlighting high-traffic zones and unusual activity).

### 2️⃣ Anomalies in Building Sensor Data
+ Energy consumption on the 3rd floor remains high even during weekends: Potential causes could be ongoing construction or unauthorized high-energy use.  
+ CO₂ Levels Peaks (June 7 & 8) 🌫: The server room showed extremely high CO₂ levels, affecting employee presence.  
+ Hazium Gas Concentration Spikes (June 11th) ☣️: Notable levels across all floors, possibly linked to unauthorized entries.
  ![image](https://github.com/user-attachments/assets/1a095860-6fe5-42fc-a0c2-2ca8b2960126)
  Time Series of Hazium Concentration
  ![image](https://github.com/user-attachments/assets/a2a799e6-a70d-4b39-b896-9b1d6379c40c)
  Time Series of CO₂ Concentration
+ Boiler Anomaly 🔥: Higher water temperature at night instead of peak solar hours, indicating a sensor misconfiguration.
  ![image](https://github.com/user-attachments/assets/5ddd630f-d739-4afb-8fe4-77a3ad632d51)
  Power Consumption Heatmap

### 3️⃣ Security Concerns & Prox Card Misuse
+ CEO Sten Sanjorge Jr’s Prox Card Activity: Anomalous midnight entry on June 1st/2nd—unusual for an executive.  
+ Geneviere Florez's Card Reissues (5 Times!): Frequent replacement suggests a potential security risk.  
+ Discrepancies in Check-ins: Nicoloi Cello and Raphale Faraldo showed conflicting check-in locations (likely due to mobile robot scans).

  ![image](https://github.com/user-attachments/assets/f3f5f2e3-d9d7-4747-875c-784da82224e0)  
  ![image](https://github.com/user-attachments/assets/090e2ba4-3852-4908-8007-e071f4ff3b69)  
  Prox Card Entry Timeline Chart 

## 🛠 Data Analysis & Visualization Methods
Tools & Technologies

+ Python (Pandas, NumPy, Matplotlib, Seaborn) 🐍: Data processing & visualization.  
+ Tableau 📊: Interactive dashboards for visual analytics.  
+ QGIS 🗺: Geospatial visualization of proximity zones.

Feature Engineering & Anomaly Detection
+ Analyzed work shift patterns using time series clustering.  
+ Used statistical thresholds (Mean ± 10σ) for CO₂ & Hazium detection.  
+ Applied correlation analysis to understand building energy dependencies.  
+ Employed rule-based anomaly detection for prox card inconsistencies.

## 🏆 Key Insights & Recommendations
+ ✅ Security Enhancements 🔐: Strengthen prox card authentication and investigate unusual midnight entries.  
+ ✅ Energy Optimization ⚡: Identify inefficient HVAC zones and reduce 3rd-floor energy consumption.  
+ ✅ Hazium Monitoring ☣️: Deploy additional sensors to track potential hazards in real time.  
+ ✅ Machine Learning Integration 🤖: Future work will use predictive models to optimize HVAC controls.

  ![image](https://github.com/user-attachments/assets/68754832-4994-44d1-8a31-fc02cf5d4b7d)
  ![image](https://github.com/user-attachments/assets/1a3ac618-6d40-48c7-819a-93820b903459)
  Anomaly Detection

## 📌 Future Scope
+ 🚀 Real-Time Monitoring System: Develop a dashboard for live anomaly detection.  
+ 🔍 Predictive Analytics for HVAC Optimization: Use AI to control building climate dynamically.  
+ 📈 Expand Sensor Networks: Enhance environmental & security monitoring with more detectors.

Final Report: reports/GASTech_Report.pdf
## 🤝 Contributors
👨‍💻 Parth Keyur Gawande  
👨‍💻 Nikhil Satish Suryawanshi  
👨‍💻 Sarthak Rajendra Bora
