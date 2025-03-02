# 🏥 Hospital Patient Analysis & ML Prediction Dashboard

## 📌 Project Overview  
This project is a **Hospital Patient Analysis Dashboard** designed to provide insights into **patient admissions, demographics, wait times, and referral sources** using **Power BI**. Additionally, **machine learning models** were implemented to predict **patient admission likelihood and estimated wait times**, enhancing hospital operational efficiency.

## 🎯 Key Objectives  
- Analyze **patient admission trends** and demographics (**age, gender, race**).  
- Evaluate **hospital system efficiency** based on **wait times and referral sources**.  
- Implement **ML models (Random Forest, XGBoost)** to predict **patient admissions and wait times**.  
- Provide **actionable insights** to optimize **resource allocation and patient care**.  

## 📂 Data Description  
The dataset consists of the following features:
- **Patient ID** → Unique identifier for each patient.  
- **Admission Date** → Date of patient admission.  
- **Gender, Age, Race** → Patient demographic details.  
- **Referral** → Source of patient referral (e.g., Orthopedics, Neurology).  
- **Admission** → Patient admission status (**Admitted / Not Admitted**).  
- **Score** → Severity score related to the patient's condition.  
- **Waittime** → Time before receiving medical attention.  
- **Case Manager** → Assigned case manager for patient care.  

## 📊 Visualizations & Insights  
✔ **Patient Status** → Bar chart showing **admitted vs. not admitted** patients.  
✔ **Admission Trends** → Line chart displaying **monthly patient admissions**.  
✔ **Patient Demographics** → **Pie charts** for **gender & race distribution**.  
✔ **Referral Analysis** → **Bar chart** showing **patients referred by each specialty**.  
✔ **Wait Time Efficiency** → Pie chart categorizing patients by wait-time efficiency.  
✔ **Actual vs. Predicted Wait Time** → **Clustered Column Chart** comparing **ML predictions vs. actual wait times**.  

## 📌 Machine Learning Integration  
- **ML Models Used:** **Random Forest (Admission Prediction), XGBoost (Wait Time Prediction)**.  
- **Feature Engineering** applied to transform **categorical variables** for ML training.  
- **DAX-powered KPIs** to track ML prediction performance against actual hospital data.  

## 🔹 KPIs (Key Performance Indicators)  
- **Total Patients** → Count of patients in the dataset.  
- **Admission Rate (%)** → Percentage of patients admitted.  
- **Average Wait Time** → Time patients spend before receiving care.  
- **Predicted vs. Actual Wait Time Deviation** → ML model accuracy measure.  
- **Patients by Referral Source** → Total number of patients referred by specialty.  

## 🛠️ Technologies Used  
- **Power BI** → Interactive dashboards & data visualizations.  
- **DAX (Data Analysis Expressions)** → Custom KPIs & calculations.  
- **Python (Pandas, Scikit-learn, XGBoost)** → ML model development.  
- **Power Query** → Data transformation & preprocessing.  
- **Power BI Service** → Report publishing & automated data refresh.  

## 📌 How to Use  
1️⃣ **Download** the Power BI (`.pbix`) file.  
2️⃣ **Open** it in **Microsoft Power BI Desktop**.  
3️⃣ **Explore** the interactive dashboard with filters & slicers.  
4️⃣ **Analyze ML predictions** for **admission probability & wait times**.  

