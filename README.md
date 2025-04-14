# Predicting-Logistics-Delays-with-Smart-Supply-Chain-Data

**Author:** Melissa Catherine Rajamanuvel  
**Program:** Data Science, University of Wisconsin–Madison  

---

## Project Overview

This project analyzes real-time logistics data enhanced with IoT sensor inputs to predict shipment delays and uncover root causes. Inspired by FWF’s commitment to data-driven freight optimization, the project demonstrates how data analytics can proactively support logistics efficiency, route planning, and capacity utilization.

---

## Dataset

- **Source:** Kaggle (Smart Logistics Supply Chain Dataset)
- **Features:**  
  - Timestamp, Asset ID, Location  
  - Shipment Status, Inventory Levels  
  - Temperature, Humidity  
  - Traffic Status, Waiting Time  
  - Asset Utilization, Demand Forecast  
  - Target: `Logistics_Delay` (1 = delayed, 0 = on time)

---

## Goals

- Understand **when and why** delays happen across months
- Identify key risk factors (traffic, weather, demand spikes)
- Build a predictive model for **logistics delay classification**

---

## Key Steps

### ETL
- Cleaned and preprocessed 2024 shipment data
- Handled missing values, unified column names

### Exploratory Analysis
- Monthly breakdown of delay rates
- Analyzed traffic trends, waiting times, and utilization
- Highlighted seasonal congestion and underutilization patterns

### Predictive Modeling
- Used **Random Forest** with encoded categorical variables
- Achieved **74% accuracy**  
- Identified most influential features:
  - Traffic Status (Heavy, Detour)
  - Waiting Time
  - Asset Utilization
  - Demand Forecast

---

## Insights

- **Delays peak** in months with high demand and poor utilization
- **Heavy traffic and detours** are the strongest predictors of delay
- **Proactive planning** using analytics can reduce risk and improve reliability

---

## Files Included

- `smart_logistics_dataset.csv`: Dataset used
- `logistics_delay_prediction.ipynb`: Full notebook with analysis + model

---

## Tools & Libraries

- Python (Pandas, Seaborn, Matplotlib)
- Scikit-learn (RandomForest, OneHotEncoder)
- Jupyter Notebook

---

## Contact

Feel free to reach out for collaboration or questions
---

