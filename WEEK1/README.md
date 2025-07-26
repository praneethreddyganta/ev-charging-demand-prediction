# Week 1 – EV Vehicle Charging Demand Prediction

**Notebook:** `EV_Vehicle_Charging_Demand_Prediction.ipynb`

---

## 📊 Project Overview

This project focuses on analyzing electric vehicle (EV) registration data across different regions to understand charging demand trends. It serves as the foundational step for forecasting EV adoption in future weeks.

---

## 📁 Files Included

- `EV_Vehicle_Charging_Demand_Prediction.ipynb` – Notebook containing data loading, cleaning, and exploratory analysis
- `ev_charging_data.csv` – Raw dataset used for analysis
- `README.md` – Documentation for Week 1

---

## 🧩 Dataset Description

- **Source:** Kaggle – Electric Vehicle Population Size 2024 Dataset
- **Features:**
  - Date
  - County
  - State
  - Vehicle Primary Use
  - BEVs (Battery Electric Vehicles) Count
  - PHEVs (Plug-In Hybrid Electric Vehicles) Count
  - Electric Vehicle (EV) Total
  - Non-Electric Vehicle Total
  - Total Vehicles
  - Percent Electric Vehicles

---

## 🛠 Steps Performed

- Loaded and explored the dataset
- Handled missing values (categorical columns filled with `'Unknown'`)
- Analyzed dataset summary and distribution
- Detected and capped outliers using IQR in the `Percent Electric Vehicles` column
- Prepared the data for Week 2 modeling

---

## 📂 Project Structure

```bash
week1/
├── EV_Vehicle_Charging_Demand_Prediction.ipynb
├── ev_charging_data.csv
└── README.md
