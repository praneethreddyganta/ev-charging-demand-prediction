# ev-charging-demand-prediction
EV_Vehicle_Charging_Demand_Prediction

Week 1 Project Submission
Date: Saturday, July 19, 2025
Project Overview
This project aims to forecast electric vehicle (EV) adoption and charging demand based on registration data across regions. The analysis helps urban planners and policymakers anticipate infrastructure needs and plan more efficient EV charging networks.
Problem Statement
Given a dataset that includes date, county, state, vehicle type, and counts of registered electric and non-electric vehicles, the objective is to analyze historical trends and prepare the data for forecasting EV adoption and charging demand.
Dataset Description
Source: [Kaggle: Electric Vehicle Population Size 2024 Dataset]
Columns:
Date
County
State
Vehicle Primary Use (Passenger/Truck)
Battery Electric Vehicles (BEVs) count
Plug-In Hybrid Electric Vehicles (PHEVs) count
Electric Vehicle (EV) Total
Non-Electric Vehicle Total
Total Vehicles
Percent Electric Vehicles
What’s Included
project_notebook.ipynb: The Colab notebook with data cleaning, exploration, and preprocessing.
ev_charging_data.csv: The dataset used for analysis.
Steps Performed
Loaded and explored the dataset
Checked for missing values and filled them with 'Unknown' for categorical columns
Explored the dataset’s structure and summary statistics
Detected and capped outliers in the Percent Electric Vehicles column using IQR
Prepared data for possible future modeling
How to Use
Download the notebook (.ipynb) and dataset (.csv) from this repository.
Open the notebook in Google Colab or Jupyter.
Run the notebook cells in order to reproduce the data exploration and cleaning steps.
Acknowledgements
Dataset: [Kaggle EV Population Size 2024]
Guidance: AICTE Skill4Future Internship
