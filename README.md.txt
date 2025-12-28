# Heart Disease Prediction Dashboard

## Project Description
This project is a **Power BI dashboard** built to analyze and visualize clinical and demographic data of patients to identify the risk of heart disease. The dashboard provides both high-level overviews and detailed patient-level insights, helping clinicians or data analysts understand patterns, risk factors, and patient stratification.

The project includes:
- Data cleaning and transformation using **Python**
- Visual analysis and KPI dashboards in **Power BI**
- Risk stratification for high-risk patients based on clinical indicators

---

## Data Source
- Dataset: **Heart_Disease_Prediction_Cleaned.csv**  
- Note: Data is **anonymized** and contains no personally identifiable information.  
- Features include: Age, Sex, Chest Pain Type, Blood Pressure, Cholesterol, Fasting Blood Sugar, ECG Results, Max Heart Rate, Exercise Angina, ST Depression, Slope of ST, Number of Vessels Fluro, Thallium Scan, Heart Disease Outcome

---

## Key KPIs & Visual Summary
The dashboard includes the following pages:

**Page 1: Heart Disease Overview**
- Total patients
- % with heart disease
- Average age and cholesterol
- Visuals by sex, chest pain type, and age distribution

**Page 2: Clinical Metrics**
- Detailed analysis of cholesterol, blood pressure, Max HR
- Exercise Angina prevalence
- Interactive slicers for demographic and clinical features

**Page 3: Patient Metrics**
- Box plots and histograms for cholesterol and Max HR
- Distribution of number of vessels affected
- Thallium scan summary

**Page 4: High-Risk Patient Analysis**
- Risk stratification: High Risk vs Low Risk
- Scatter plot: Cholesterol vs Max HR, bubble size = ST Depression
- Heatmap: Age × Cholesterol with % Heart Disease
- Bar chart: Count of High vs Low Risk patients
- Insight text summarizing key findings

---

## How to Use / Open the PBIX File
1. Download the project folder from this repository.  
2. Open **Heart_Disease_Dashboard.pbix** in **Power BI Desktop** (version 2022 or later recommended).  
3. Ensure the **CSV dataset (Heart_Disease_Prediction_Cleaned.csv)** is in the same folder or linked properly in Power BI.  
4. Interact with slicers and visuals to explore the data.  
5. Export or publish to **Power BI Service** for sharing with stakeholders.

---

## Tools & Technologies
- **Python**: Data cleaning and preprocessing  
- **Power BI Desktop**: Dashboard building and visualization  
- **GitHub**: Project version control and sharing  

---

## Optional Notes
- All risk calculations and categories are **clinically informed** (High Risk if Heart Disease = 1 AND at least one risk indicator is present).  
- Dashboard is designed for educational and portfolio purposes; not for real-world clinical decision making.

