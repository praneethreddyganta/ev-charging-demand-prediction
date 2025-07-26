# EV Charging Demand Prediction

**EV_Vehicle_Charging_Demand_Prediction**

---

## 📊 Project Overview

This project focuses on analyzing electric vehicle (EV) registration data to understand EV adoption trends and charging demand. Cleaned data from this step is used for forecasting in Week 2.

---

## 🚧 Problem Statement

Given a dataset containing location-wise EV registrations, our goal is to analyze patterns, clean inconsistencies, and make the data ready for future prediction models.

---

## 📁 Dataset Description

- **Source:** [Kaggle – Electric Vehicle Population Size 2024]
- **Important Columns:**
  - Date
  - County
  - State
  - Vehicle Type (Passenger/Truck)
  - Battery Electric Vehicles (BEVs)
  - Plug-in Hybrid Electric Vehicles (PHEVs)
  - EV Total, Non-EV Total, Total Vehicles
  - Percent Electric Vehicles

---

## 📦 What’s Included

- `EV_Vehicle_Charging_Demand_Prediction.ipynb`: Data cleaning and EDA notebook  
- `ev_charging_data.csv`: Raw EV dataset used for cleaning  
- `README.md`: Project documentation for Week 1

---

## ✅ Steps Performed

- Loaded dataset and explored basic info  
- Checked and filled missing values  
- Handled outliers using IQR technique  
- Performed basic data visualization  
- Saved cleaned dataset for next week's forecasting

---

## 📂 Project Structure

```bash
week1/
├── EV_Vehicle_Charging_Demand_Prediction.ipynb
├── ev_charging_data.csv
└── README.md

## How To Use

'''bash

1. Clone or download the repository.
2. Navigate to the `week1/` folder.
3. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
4. Upload `ev_charging_data.csv` when prompted.
5. Run the notebook to analyze EV registration trends and clean the data.
6. Leverage any additional files/scripts to extend or customize your analysis.

---

## 🙌 Acknowledgements
''' bash
- Internship: AICTE Skill4Future
- Mentor: Raghunandan Sir
- Dataset: Kaggle – Electric Vehicle Population Dataset
- Tools Used: Python, Pandas, Matplotlib, Google Colab


