# EV Charging Demand Prediction

**EV_Vehicle_Charging_Demand_Prediction**

---

## Project Overview

This project focuses on analyzing electric vehicle (EV) registration data to understand EV adoption trends and charging demand. The cleaned dataset is used in Week 2 for forecasting future adoption rates.

---

## Problem Statement

Given a dataset containing regional EV registrations, the objective is to clean and analyze the data to prepare it for predictive modeling. This includes handling missing values, removing outliers, and basic visualizations.

---

## Dataset Description

- **Source:** [Kaggle – Electric Vehicle Population Size 2024]
- **Format:** CSV  
- **Important Columns:**
  - Date
  - County
  - State
  - Vehicle Primary Use
  - BEV and PHEV counts
  - Total EV, Non-EV, and % EV Vehicles

---

## What’s Included

- `EV_Vehicle_Charging_Demand_Prediction.ipynb` – Jupyter/Colab notebook with data cleaning and EDA  
- `ev_charging_data.csv` – Original dataset used  
- `README.md` – Documentation for Week 1

---

## Steps Performed

- Loaded dataset and explored structure  
- Filled missing values for categorical columns  
- Identified and capped outliers using IQR  
- Visualized trends and data summary  
- Prepared and exported cleaned dataset

---

## How to Use

1. Download or clone this repository.
2. Navigate to the `week1/` folder.
3. Open `EV_Vehicle_Charging_Demand_Prediction.ipynb` using Google Colab or Jupyter.
4. Upload the `ev_charging_data.csv` file when prompted.
5. Run the notebook step-by-step to understand and clean the data.

---

## Acknowledgements

- **Internship:** AICTE Skill4Future Internship  
- **Dataset:** Kaggle – Electric Vehicle Population Dataset  
- **Mentor & Guidance:** Raghunandan Sir

---

## 📂 Project Structure

```bash
week1/
├── EV_Vehicle_Charging_Demand_Prediction.ipynb
├── ev_charging_data.csv
└── README.md
