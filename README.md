# 🏥 Hospital Emergency Room Analysis Dashboard

## 📌 Project Overview  
The **Hospital Emergency Room (ER) Analysis Dashboard** is built in **Power BI** to provide **real-time insights** into **ER performance metrics**. It enables stakeholders to **monitor patient flow, wait times, referrals, and satisfaction scores** to optimize emergency room operations and improve patient care.

This project demonstrates my expertise in:  
✔ **Data Analysis & Business Intelligence (BI)**  
✔ **Data Modeling & SQL for ETL**  
✔ **Power BI Dashboard Development**  
✔ **Healthcare Data Analytics & Performance Monitoring**  

---

## 🚀 Problem Statement  
Hospitals often struggle with **ER inefficiencies**, including:  
-  **Long wait times** causing patient dissatisfaction.  
-  **Lack of visibility** into peak hours, patient demographics, and referral trends.  
-  **Limited insights** into staff allocation and resource optimization.  
-  **Challenges in tracking admission rates, referrals, and operational efficiency.**  

Without **real-time monitoring**, **decision-makers** cannot effectively allocate resources, improve patient care, or optimize hospital operations.

---

## ✅ Solution Overview  
The **Power BI Dashboard** enables:  
📌 **Real-time tracking of ER performance metrics**.  
📌 **Daily, Monthly, and Consolidated views** for **trend analysis and performance monitoring**.  
📌 **Patient-level insights** to improve **operational decision-making**.  
📌 **Interactive filters** for **date selection, department breakdown, and demographic analysis**.  

---

## 🎯 Key Performance Indicators (KPIs)  

- **Number of Patients**: Tracks total ER visits per day, visualized using an **area sparkline** to monitor **daily trends and peak hours**.  
- **Average Wait Time**: Calculates **average wait times** before a patient is attended to, helping in **staffing and resource allocation**.  
- **Patient Satisfaction Score**: Monitors **daily satisfaction levels** based on **feedback scores** to track service quality.  
- **Number of Patients Referred**: Tracks **referrals to other departments**, identifying areas that need **additional resources**.  

---

## 🛠 Tools & Technologies Used  
- 📊 **Power BI** – Data visualization & dashboard creation.  
- 🛢 **SQL** – Data extraction, transformation, and preparation.  
- 🐍 **Python (Pandas, NumPy, Matplotlib, Seaborn)** – Data cleaning & analysis.  
- ☁ **Azure/AWS Cloud Services** – Data storage and management.  
- 📂 **Excel & CSV** – Raw data collection and preprocessing.  

---

## 📊 Data Model & Structure  

The **data model** integrates **patient details, admissions, referrals, satisfaction scores, and wait times** into a **relational database**.

### 📌 Data Model Screenshot  
![Data Model](https://github.com/muralikrishna-v/Healthcare-emergencyroom-analysis_powerBI/blob/main/hospital_eranalysis_datamodelling.png)  

📌 **Data Sources**:  
- **Patient Admissions Data**  
- **ER Wait Time Logs**  
- **Referral & Department Allocation**  
- **Satisfaction Survey Data**  

📌 **Key Tables & Relationships**:  
- **Patients Table** (ID, Name, Age, Gender, Race, Admission Status).  
- **Admissions Table** (Admission Date, Wait Time, Department, Referrals).  
- **Satisfaction Scores Table** (Patient ID, Score, Comments).  
- **Time Analysis Table** (Daily/Hourly Trends).  

---

## 📊 Hospital Emergency Room Dashboard Overview  

This **Power BI dashboard** includes **four key analytical views**:  

1️⃣ **Monthly View** – Monitors **key performance metrics** to identify trends and areas for improvement.  
2️⃣ **Consolidated View** – Aggregates data over a **customizable date range** for deeper trend analysis.  
3️⃣ **Patient-Level Details** – Provides **granular insights into individual patient data**.  
4️⃣ **Comprehensive Summary View** – Combines all findings to deliver **clear, actionable insights** for stakeholders.  

📌 **Dashboard Screenshot**:  
![Dashboard Overview](images/hospital_dashboard_overview.png)  

### 📌 Features & Insights  

- **Patient Admission Status**: Tracks **admitted vs. non-admitted patients**.  
- **Patient Age Distribution**: Groups patients into **10-year intervals** for demographic insights.  
- **Department Referrals**: Analyzes **which departments receive the most ER referrals**.  
- **Timeliness of Care**: Measures the **percentage of patients seen within 30 minutes**.  
- **Gender Analysis**: Provides **visual distribution of patients by gender**.  
- **Racial Demographics**: Displays **patient breakdown by race**.  
- **Time Analysis**: Evaluates **patient volume by day and hour** to identify **busiest periods**.  

📌 **Key Findings**  
- **Peak patient admissions occur between 10 AM – 4 PM**, leading to **longer wait times**.  
- **Referrals to Cardiology and Orthopedics** are highest, indicating a **need for better triaging**.  
- **Wait times tend to increase on weekends**, suggesting **a need for improved weekend staffing**.  

---

## 📈 Methodology & Data Processing  

1️⃣ **Data Collection & Cleaning**  
   - Extracted raw hospital data from **SQL databases and Excel files**.  
   - **Cleaned data in Python (Pandas)** to remove duplicates and handle missing values.  

2️⃣ **Data Transformation & Modeling**  
   - Used **SQL queries** for **data aggregation and structuring**.  
   - Established **Power BI relationships** between tables for seamless integration.  

3️⃣ **Data Analysis & Dashboard Development**  
   - Built **interactive Power BI visualizations** with **DAX calculations**.  
   - Integrated **dynamic filters and slicers** to allow users to **explore different date ranges, demographics, and referral patterns**.  

---

## 📌 Key Takeaways & Business Recommendations  

✅ **Optimize Staffing & Reduce Wait Times** – Increase staffing **during peak hours** to **minimize long wait times**.  
✅ **Enhance Patient Satisfaction** – Address days with **low satisfaction scores** by **adjusting operational efficiency**.  
✅ **Department Resource Allocation** – Allocate **more resources** to departments **with high referrals**.  
✅ **Predictive Analysis** – Implement **machine learning models** to **forecast hospital demand trends**.  

📌 **Comprehensive Summary View Screenshot**:  
![Summary View](images/hospital_summary_view.png)  

---


