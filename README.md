# ✈️ Airline Performance Analysis

This project analyzes U.S. domestic flight data (5.8M+ records) to compare airline performance, operational efficiency, and route-level reliability. It includes both descriptive analytics and a predictive delay model.

## 🔍 Objective

- Compare U.S. airlines by average delays, cancellations, and distance
- Identify time-based and airport-specific patterns
- Build a Random Forest model to predict if a flight will be delayed >15 minutes

## 📊 Key Insights

- **Best Airlines**: Alaska Airlines and Delta Air Lines had the lowest arrival delays.
- **Best Time to Fly**: Flights departing between 5–8 AM had the least delays.
- **Worst Airports**: JFK and LaGuardia showed highest taxi-out times; Wilmington & Trenton had worst delay rates.
- **Main Causes of Delay**: Late aircraft and airline-related factors were dominant.
- **Modeling**: Random Forest achieved 78% accuracy but struggled with class imbalance.

## 📁 Project Files

- `Airline_Comparison_Taps.ipynb` – Full notebook: cleaning, analysis, modeling
- `flights_cleaned.csv` – Final cleaned dataset (~100k sample rows)
- Visuals: Charts showing delays, volume, route risk, etc.

## 🛠 Tools & Libraries

- Python (Pandas, Seaborn, Matplotlib, SHAP, Scikit-learn)
- Google Colab
- Plotly (interactive visualizations)

## 📌 Next Steps

- Add weather + aircraft type data
- Improve class balancing in model
- Deploy dashboard with Streamlit or Dash
 
