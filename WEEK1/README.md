# EV Charging Demand Prediction

**EV_Vehicle_Charging_Demand_Prediction**

---

## Project Overview

This project aims to analyze historical electric vehicle (EV) registration data across different counties and states in order to understand the demand for EV charging. The cleaned and structured dataset will serve as the foundation for forecasting models developed in the upcoming weeks. The analysis supports better planning of infrastructure like charging stations and public EV support systems.

---

## Problem Statement

Given a dataset that includes registration details like date, location, vehicle type, and counts of electric and non-electric vehicles, the goal is to analyze trends, handle inconsistencies, and prepare the data for building a predictive model for EV charging demand.

---

## Dataset Description

- **Source:** [Kaggle – Electric Vehicle Population Size 2024 Dataset]
- **Features/Columns Include:**
  - Date
  - County
  - State
  - Vehicle Primary Use (Passenger or Truck)
  - Battery Electric Vehicles (BEVs) count
  - Plug-In Hybrid Electric Vehicles (PHEVs) count
  - Electric Vehicle (EV) Total
  - Non-Electric Vehicle Total
  - Total Vehicles
  - Percent of Electric Vehicles

---

## What’s Included

- `EV_Vehicle_Charging_Demand_Prediction.ipynb` – Colab notebook containing data loading, cleaning, and analysis
- `ev_charging_data.csv` – The original dataset used for the analysis
- `README.md` – This file (documentation for Week 1 work)

---

## Steps Performed

- Loaded and explored the dataset
- Checked and handled missing values (categorical values filled with `'Unknown'`)
- Summarized the dataset using statistics and visual tools
- Identified and treated outliers using IQR in `Percent Electric Vehicles`
- Prepared cleaned dataset for forecasting models in Week 2

---

## How to Use

1. Download the notebook and dataset (`.ipynb` and `.csv`).
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Upload `ev_charging_data.csv` when prompted.
4. Run the notebook cells in sequence to reproduce the results.

---

## Acknowledgements

- **Dataset Source:** [Kaggle – EV Population Size 2024 Dataset]
- **Guidance & Curriculum:** AICTE Skill4Future Internship
- **Mentor Reference:** Raghunandan Sir's GitHub projects
