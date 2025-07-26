# EV Adoption Forecasting

**EV_Adoption_Forecasting**

---

## Project Overview

This project is a continuation of Week 1's work and focuses on forecasting the future adoption of electric vehicles (EVs) using machine learning. Leveraging the cleaned dataset created in Week 1, we perform feature engineering and train a Linear Regression model to visualize upcoming EV trends across regions. This supports long-term infrastructure planning like EV charging stations.

---

## Problem Statement

Using historical EV registration data, the objective is to predict the percentage of electric vehicles over time. This helps planners and governments anticipate demand for EV infrastructure, incentives, and energy distribution.

---

## Dataset Description

- **Source:** Cleaned dataset from Week 1  
- **Format:** CSV  
- **Features/Columns Include:**
  - Date
  - County
  - State
  - Battery Electric Vehicles (BEVs)
  - Plug-In Hybrid Electric Vehicles (PHEVs)
  - Electric Vehicle (EV) Total
  - Non-Electric Vehicle Total
  - Total Vehicles
  - Percent of Electric Vehicles (Target)

---

## What’s Included

- `EV_Adoption_Forecasting.ipynb` – Notebook with forecasting model, data preprocessing, and results  
- `preprocessed_ev_data.csv` – Cleaned dataset output from Week 1  
- `forecasting_ev_model.pkl` – Trained regression model serialized using Pickle  
- `README.md` – This file (documentation for Week 2 work)

---

## Steps Performed

- Loaded cleaned dataset from Week 1  
- Conducted data preprocessing and transformation  
- Performed train-test split  
- Trained Linear Regression model on target feature  
- Visualized model performance and predictions  
- Serialized the trained model using Pickle for future reuse

---

## How to Use

1. Download the notebook, dataset, and `.pkl` model file.
2. Open `EV_Adoption_Forecasting.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Upload the `preprocessed_ev_data.csv` file when prompted.
4. Run all notebook cells to visualize forecast results.
5. Use the `forecasting_ev_model.pkl` model in other apps or dashboards for predictions.

---

## Acknowledgements

- **Dataset Source:** Prepared from Week 1 Dataset (originally from [Kaggle – EV Population Size 2024])  
- **Guidance & Curriculum:** AICTE Skill4Future Internship  
- **Mentor Reference:** Raghunandan Sir's GitHub repositories and walkthroughs

week2/
├── EV_Adoption_Forecasting.ipynb       # Colab/Jupyter notebook for training & forecasting
├── preprocessed_ev_data.csv            # Cleaned dataset used as input
├── forecasting_ev_model.pkl            # Trained Linear Regression model (Pickle)
└── README.md                           # Week 2 documentation
