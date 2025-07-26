# EV Charging Demand Prediction – Full Project

**EV_Vehicle_Charging_Demand_Prediction + EV_Adoption_Forecasting**

---

## Project Overview

This project was developed as part of the **AICTE Skill4Future Internship** and aims to analyze and forecast electric vehicle (EV) adoption and charging demand using real-world registration data.  
The project is divided into two phases:

- **Week 1:** Data Cleaning, Analysis, and Preparation  
- **Week 2:** Forecasting EV Adoption using Machine Learning  

The goal is to support better planning for EV infrastructure like charging stations and policy decisions.

---

## Problem Statement

With rising EV adoption, urban planners and governments need to predict demand for EV-related infrastructure.  
This project analyzes EV registration data (state, county, date, vehicle type) to:

- Understand current EV usage trends  
- Prepare data for modeling  
- Predict future EV adoption using ML models

---

## Dataset Description

- **Source:** [Kaggle – Electric Vehicle Population Size 2024 Dataset]  
- **Columns Include:**
  - Date
  - County
  - State
  - Vehicle Type
  - Battery Electric Vehicles (BEVs)
  - Plug-In Hybrid Electric Vehicles (PHEVs)
  - Electric Vehicle Total
  - Non-Electric Vehicle Total
  - Total Vehicles
  - Percent Electric Vehicles

---

## Week 1 – Data Cleaning & Analysis

### 📘 Objective:
- Analyze raw dataset, clean inconsistencies, fill missing values, and visualize trends.

### 📁 Files in `week1/`:
- `EV_Vehicle_Charging_Demand_Prediction.ipynb`  
- `ev_charging_data.csv`  
- `README.md`

### ✅ Key Steps:
- Missing value handling  
- Data exploration  
- Outlier detection using IQR  
- Saving cleaned dataset for Week 2  

---

## Week 2 – EV Adoption Forecasting

### 📗 Objective:
- Build a Linear Regression model to forecast the percentage of EV adoption over time.

### 📁 Files in `week2/`:
- `EV_Adoption_Forecasting.ipynb`  
- `preprocessed_ev_data.csv`  
- `forecasting_ev_model.pkl`  
- `README.md`

### ✅ Key Steps:
- Feature engineering  
- Model training using scikit-learn  
- Model serialization using Pickle  
- Forecast visualization

---

## How to Use

1. Clone or download this repository.
2. Navigate to `week1/` or `week2/` folder.
3. Open the corresponding `.ipynb` file using [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
4. Upload the corresponding dataset when prompted.
5. Run the notebook cells to perform analysis or forecasting.
6. Use the `.pkl` model (Week 2) for external applications.

---

## Acknowledgements

- **Internship:** AICTE Skill4Future  
- **Mentor:** Raghunandan Sir  
- **Dataset:** [Kaggle – Electric Vehicle Population Size 2024 Dataset]  
- **Tools Used:** Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Google Colab, Pickle

---

## 📂 Overall Project Structure

```bash
ev-charging-demand-prediction/
├── week1/
│   ├── EV_Vehicle_Charging_Demand_Prediction.ipynb
│   ├── ev_charging_data.csv
│   └── README.md
│
├── week2/
│   ├── EV_Adoption_Forecasting.ipynb
│   ├── preprocessed_ev_data.csv
│   ├── forecasting_ev_model.pkl
│   └── README.md
│
└── README.md   # This main project README file (You are reading it)
