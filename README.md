# 🏥 Hospital Emergency Room Dashboard

[![Power BI](https://img.shields.io/badge/Tool-Power%20BI-blue)](https://powerbi.microsoft.com/) 
[![Status](https://img.shields.io/badge/Status-Completed-success)](#) 
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
---

This repository contains the **Hospital Emergency Room Dashboard**, designed to analyze and optimize emergency room operations. It leverages insights from patient demographics, admission patterns, satisfaction levels, and operational metrics to enhance patient care and resource allocation.

---

## 📑 Overview

The **Hospital Emergency Room Dashboard** is a comprehensive solution for:
- **Patient Flow Analysis**: Tracking wait times and admission rates.
- **Resource Utilization**: Identifying department referral trends for better staffing.
- **Quality Assessment**: Using satisfaction scores to improve patient experience.
- **Demographic Studies**: Analyzing age, race, and gender distributions.
- **Operational Efficiency**: Monitoring peak busy periods for resource optimization.

---

## 🗂️ Data Dictionary

**Source:** https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=Hospital+ER.csv

| **Field Name**            | **Data Type**      | **Description**                                                                 |
|----------------------------|--------------------|---------------------------------------------------------------------------------|
| **Patient ID**             | Alphanumeric      | Unique identifier assigned to each patient to ensure tracking and privacy.      |
| **Patient Admission Date** | DateTime          | Timestamp capturing the patient's arrival at the emergency room.                |
| **Patient First Initial**  | Char(1)           | First letter of the patient’s first name, ensuring compliance with HIPAA/GDPR.  |
| **Patient Last Name**      | String            | Patient’s last name; may be anonymized as per privacy protocols.                |
| **Patient Gender**         | Enum              | Patient's gender identity (e.g., Male, Female, Other, Nonbinary).               |
| **Patient Age**            | Integer           | Age of the patient at the time of admission.                                    |
| **Patient Race**           | String            | Self-reported racial or ethnic identity.                                        |
| **Department Referral**    | String            | Department the patient was referred to, such as Cardiology or Orthopedics.      |
| **Patient Admin Flag**     | Boolean           | Indicates if the patient was admitted (True) or discharged/referred (False).    |
| **Patient Satisfaction Score** | Integer     | Score reflecting the patient’s experience, typically on a 1-10 scale.           |
| **Patient Wait Time**      | Time              | Duration between the patient's arrival and first contact with medical staff.     |
| **Patients CM**            | String            | Case manager or team assigned to coordinate the patient’s care.                 |

---

## 🔑 Key Insights

### 1️⃣ Patient Wait Time & Satisfaction
- **Average Wait Time**: 35.3 minutes.
- Indicates a potential bottleneck in patient flow, necessitating strategies to enhance operational efficiency. 
- **Satisfaction Score**: 4.99 out of 10.
- Reflects moderate satisfaction, highlighting areas for improvement in patient experience.

### 2️⃣ Departmental Referrals
- **Most Common Referrals**:
  - General Practice (1,840 cases)
  - Orthopedics (995 cases)
  - **Implication**: Higher referral rates in General Practice and Orthopedics indicate resource demands in these departments.

### 3️⃣ Peak Busy Periods
- **Busiest Days**: Saturday (1,377 patients), Thursday (1,322 patients), Sunday (1,318 patients) .  
- **Busiest Hours**: 11 AM, 1 PM, 7 PM, 11 PM.
- **Implication**: Staffing adjustments are critical during peak days and hours to manage patient volume effectively.

### 4️⃣ Patient Demographics
- **Age Groups**: Adults (30–39 years, 1,200 patients).  
- **Race**: Largest group is White (2,571 patients).

### 5️⃣ Admission Patterns
- **Admitted Patients**: 50% (4,612 patients).  
- **Treated and Released**: 50% (4,604 patients).
- **Implication**: Balanced admission patterns suggest optimized use of inpatient facilities.

---

## 🎯 Recommendations
1. **Operational Efficiency**: Reduce average wait times by streamlining patient flow.
2. **Enhanced Satisfaction**: Identify pain points affecting satisfaction scores.
3. **Resource Allocation**: Scale resources for high-demand departments.
4. **Staffing**: Optimize staffing during peak busy periods.
5. **Tailored Care**: Address needs of diverse demographics.

---

## 🛡️ Data Privacy and Compliance

This project complies with **HIPAA** and **GDPR** regulations. Sensitive fields like `Patient ID`, `Name`, `Race`, and `Gender` are anonymized or handled with care to protect patient privacy.

---

## 📊 Dashboard Features

### 1️⃣ Monthly View  
- **Metrics**: Admissions, referrals, satisfaction, demographics, and wait times.  

### 2️⃣ Holistic View  
- **Insights**: Aggregated data for trend analysis and decision-making.  

### 3️⃣ Patient Details  
- **Details**: Granular patient-level data for in-depth analysis.

---

## 💻 Technical Steps

### Project Workflow
1. Requirement Gathering
2. Data Cleaning & Quality Check
3. Data Modeling & Processing
4. DAX Calculations & Chart Development
5. Dashboard Development & Insights Generation

---
## How to Access  

1. Download the Powerbi from this repository.  
2. Open the `.pbix` file in Powerbi Desktop.  
3. Explore interactive visualizations and uncover insights.  

---

## License 📝  

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.  

---

## Contact  

For inquiries or collaboration, please feel free to reach out:  
- **Email**: adnan.bava123@gmail.com   
---




