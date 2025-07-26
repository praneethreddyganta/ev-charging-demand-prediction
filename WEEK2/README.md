# EV Adoption Forecasting

**EV_Adoption_Forecasting**

---

## Project Overview

This project is a continuation of Week 1's work and focuses on forecasting the adoption of electric vehicles using machine learning. Based on the cleaned EV registration dataset, we apply data preprocessing, build a Linear Regression model, and visualize future trends in EV adoption across regions.

---

## Problem Statement

Given a preprocessed dataset of electric vehicle registrations, the objective is to predict the number or proportion of electric vehicles in the future. The goal is to assist governments and urban planners with insight on infrastructure requirements like public EV charging stations.

---

## Dataset Description

- **Source:** Cleaned and prepared data from Week 1
- **Format:** CSV
- **Target Variable:** Percent Electric Vehicles

---

## What’s Included

- `EV_Adoption_Forecasting.ipynb` – Jupyter/Colab notebook that contains the forecasting model and visualizations
- `preprocessed_ev_data.csv` – Cleaned dataset used to train the model
- `forecasting_ev_model.pkl` – Serialized model saved using Pickle
- `README.md` – This documentation file for Week 2

---

## Steps Performed

- Imported and split the dataset
- Performed feature selection and transformation
- Trained a Linear Regression model
- Visualized predictions using Matplotlib
- Saved the trained model as `.pkl` for future use or deployment

---


## How to Use

1. Download or clone this repository.
2. Open `EV_Adoption_Forecasting.ipynb` using Google Colab or Jupyter.
3. Upload the `preprocessed_ev_data.csv` file when prompted.
4. Run each cell in sequence to reproduce the forecast results.
5. Use the saved model (`.pkl`) for inference in external applications.

---


## Acknowledgements

- **Internship:** AICTE Skill4Future Internship
- **Data Source:** Prepared dataset from Week 1 (originally from Kaggle)
- **Mentor & Guidance:** Raghunandan Sir’s GitHub repositories and reference code


## 📂 Project Structure

```bash
week2/
├── EV_Adoption_Forecasting.ipynb
├── preprocessed_ev_data.csv
├── forecasting_ev_model.pkl
└── README.md

