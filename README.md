# ✈️ Flight Delay Prediction

This project analyzes and predicts flight delays using historical U.S. flight data. It includes both **Exploratory Data Analysis (EDA)** and a **Machine Learning model** to understand delay patterns and predict the likelihood of a flight being delayed.

---

## 📌 Objectives

- Perform data preprocessing and clean raw flight data.
- Conduct EDA to uncover delay trends across time, carriers, and causes.
- Train a regression model to predict arrival delays in minutes.
- Evaluate the performance and effectiveness of the model.

---

## 📊 Dataset Features

The dataset contains various features such as:

- `Month`, `Carrier`, `Airport` — for identification and temporal patterns
- `arr_flights`, `arr_del15`, `arr_cancelled`, `arr_diverted`
- Delay causes: `carrier_ct`, `weather_ct`, `nas_ct`, `security_ct`, `late_aircraft_ct`
- Delay durations: `carrier_delay`, `weather_delay`, `nas_delay`, etc.

These features help in identifying delay patterns and contributing factors.

---

## 🧪 Exploratory Data Analysis

Key EDA insights:

- Bar plots showing flight volume and delay count by month
- Heatmaps for correlation between different delay types
- Delay trends by airline/carrier
- Top airports and months with frequent delays

Visualizations are done using **Matplotlib** and **Seaborn**.

---

## 🧠 Model Development

- Model used: **XGBoost Regressor**
- Target variable: `arr_delay` (arrival delay in minutes)
- Evaluation metric: **R² Score**

The model helps estimate expected delay based on operational and environmental inputs.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Project Structure
flight-delay-prediction/
├── flight_delay_prediction.ipynb # Main notebook with EDA and model
├── presentation_deck.pdf # Project summary presentation (optional)
└── README.md # Project documentation


---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
3. Open flight_delay_prediction.ipynb in Jupyter Notebook or VSCode.
4. Run all cells sequentially.

---

## 📌 Future Improvements
Use advanced hyperparameter tuning
Add interactive dashboard using Streamlit or Dash
