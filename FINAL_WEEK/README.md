# 🔋 EV Adoption Forecasting for Washington State Counties

This project forecasts the **Electric Vehicle (EV) adoption** in counties across Washington State using time-series modeling and presents results via an interactive web dashboard.

---

## 📌 Features

- Forecast EV adoption for the **next 3 years**.
- Interactive **Streamlit dashboard** to visualize trends per county.
- Compare EV adoption growth across **multiple counties**.
- Uses historical time series data and custom features.
- Styled graphs with dark mode aesthetics and percentage change highlights.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** (Dashboard UI)
- **Pandas**, **NumPy**
- **Matplotlib** (Plotting)
- **Scikit-learn** (ML model)
- **Joblib** (Model persistence)

---

## 📁 File Structure

```
final-week/
│
├── app.py                        # Streamlit app code
├── EV_Adoption_Forecasting.ipynb# Jupyter notebook (model building and feature engineering)
├── forecasting_ev_model.pkl     # Trained model file
├── preprocessed_ev_data.csv     # Cleaned EV adoption data
├── ev-car-factory.jpg           # Image used in Streamlit UI
└── README.md                    # Project overview file
```

---

## 📊 Input Dataset Structure (`preprocessed_ev_data.csv`)

Your dataset should include the following columns:

- `County`: Name of the county
- `Date`: Monthly timestamp
- `Electric Vehicle (EV) Total`: Monthly EV count
- `county_encoded`: Encoded county value for modeling
- `months_since_start`: Relative time axis for forecasting

---

## ⚙️ Forecasting Logic

The model forecasts EV totals based on the last 6 months of historical values using:

- Lag features (`EV Total` from previous months)
- 3-month rolling mean
- Percentage change (1-month and 3-month)
- EV adoption growth slope
- Encoded county data

The prediction loop runs iteratively for **36 months** (3 years) into the future.

---

## 🎯 How to Run the Streamlit App

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name/final-week
   ```

2. **Install required libraries**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ensure these files are present**:
   - `app.py`
   - `forecasting_ev_model.pkl`
   - `preprocessed_ev_data.csv`
   - `ev-car-factory.jpg`

4. **Launch the app**:
   ```bash
   streamlit run app.py
   ```

---

## 📷 Streamlit App UI Highlights

- 🌐 Select a county from the dropdown and visualize the forecast.
- 📈 View cumulative EV adoption over time.
- 📊 Compare trends across up to 3 counties.
- ✅ View percentage growth expected for each selected region.
- 🎨 Visually appealing dashboard with modern styling.

---

## 📓 Notebook Summary (`EV_Adoption_Forecasting.ipynb`)

The notebook includes:

- Loading and preprocessing the EV dataset
- Feature engineering (lag, rolling mean, growth slope)
- Model training using regression (e.g., RandomForest, XGBoost, etc.)
- Evaluation and export of the final trained model using `joblib`

Use this notebook to reproduce the training process or improve the model.

---

## 📬 Contact

**👨‍💻 Ganta Praneeth Reddy**  
🎓 B.E. CSE (AIML), CBIT  
📧 praneethreddyganta@gmail.com  

---

## 📌 Acknowledgements

This project was developed as part of the **AICTE Internship Cycle 2 by S4F**.
