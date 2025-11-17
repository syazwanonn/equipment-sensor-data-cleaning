# Industrial Equipment Sensor Data Cleaning Project

This repository contains a complete data cleaning workflow for a 10,000-record industrial sensor dataset.  
The raw data includes mixed timestamp formats, corrupted sensor readings (temperature, pressure, vibration), 
missing values, and extreme outliers from faulty equipment.

## 📁 Project Files
- `equipment_sensors_raw.xlsx` – messy machine sensor readings  
- `equipment_sensors_clean.xlsx` – cleaned dataset  
- `data_cleaning_portfolio_notebook.ipynb` – full cleaning notebook  
- `Equipment_Sensors_Data_Cleaning_Report.pdf` – professional report  

## 🧹 Key Cleaning Steps
- Standardized timestamps (multiple formats → datetime)  
- Cleaned noisy numeric readings and removed non-numeric artifacts  
- Normalized category fields (status, operator, location, shift)  
- Replaced missing values with median values  
- Identified and handled extreme sensor outliers  
- Removed duplicate logs  

## 🎯 Outcome
A high-quality dataset ready for:
- Predictive maintenance  
- Equipment anomaly detection  
- Industrial dashboards  
- Operational analytics  

---

## 📄 Author
Mohammad Syazwan Bin Onn  
MsC in Data Science  
