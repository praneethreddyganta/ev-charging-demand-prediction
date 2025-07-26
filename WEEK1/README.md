EV Charging Demand Prediction
EV_Vehicle_Charging_Demand_Prediction

📊 Project Overview
This project focuses on analyzing electric vehicle (EV) registration data to understand EV adoption trends and charging demand. The cleaned dataset forms the basis for forecasting models in later phases of the project.

🚧 Problem Statement
Given a dataset containing location-wise EV registrations, the objective is to analyze patterns, clean inconsistencies, and prepare the data for use in future predictive models.

📁 Dataset Description
Source: Kaggle – Electric Vehicle Population Size 2024

Important Columns:

Date

County

State

Vehicle Type (Passenger/Truck)

Battery Electric Vehicles (BEVs)

Plug-in Hybrid Electric Vehicles (PHEVs)

EV Total

Non-EV Total

Total Vehicles

Percent Electric Vehicles

📦 What’s Included
EV_Vehicle_Charging_Demand_Prediction.ipynb: Jupyter notebook for data cleaning and exploratory data analysis (EDA)

ev_charging_data.csv: Raw EV dataset used for cleaning and analysis

README.md: Project documentation (this file) for Week 1

✅ Steps Performed
Loaded dataset and explored basic information

Checked for and filled missing values

Handled outliers using the IQR technique

Performed basic data visualization to uncover trends

Saved cleaned dataset for use in next week’s forecasting and modeling

📂 Project Structure
bash
week1/
├── EV_Vehicle_Charging_Demand_Prediction.ipynb
├── ev_charging_data.csv
└── README.md
🚀 How to Use
Clone or download the repository.

Navigate to the week1/ folder.

Open EV_Vehicle_Charging_Demand_Prediction.ipynb with Google Colab or Jupyter Notebook.

Upload ev_charging_data.csv when prompted.

Run the notebook cells sequentially to analyze EV registration trends and clean the data.

🙌 Acknowledgements
Internship: AICTE Skill4Future

Mentor: Raghunandan Sir

Dataset: Kaggle – Electric Vehicle Population Dataset

Tools Used: Python, Pandas, Matplotlib, Google Colab
