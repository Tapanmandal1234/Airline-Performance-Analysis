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

| Chart Title                           | Filename                       | Why Include                                    |
| ------------------------------------- | ------------------------------ | ---------------------------------------------- |
| **Average Delay by Airline**          | `avg_delay_by_airline.png`     | Shows the core performance comparison          |
| **Top 10 Most Delayed Routes**        | `top_delayed_routes.png`       | Route-specific pain points → useful & visual   |
| **Heatmap of Delay by Hour & Day**    | `delay_heatmap.png`            | Gives temporal insight — strong storytelling   |
| **Flight Volume by Airline**          | `flight_volume_by_airline.png` | Demonstrates traffic load vs performance       |
| **Flight Distance by Airline**        | `avg_distance_by_airline.png`  | Adds operational context to delay stats        |
| **Top Origin Airports by Volume**     | `top_origin_airports.png`      | Shows connection hubs — relevant for ops roles |
| **Taxi Time by Airport**              | `taxi_time_by_airport.png`     | Indicates congestion and airport performance   |
| **Turnaround Time by Tail Number**    | `turnaround_by_tail.png`       | Shows fleet reuse and operational efficiency   |
| **Weekend vs Weekday Delays**         | `weekday_vs_weekend_delay.png` | Offers human-readable timing advice            |
| **Model Evaluation Confusion Matrix** | `confusion_matrix_rf.png`      | Demonstrates modeling evaluation               |


## 🛠 Tools & Libraries

- Python (Pandas, Seaborn, Matplotlib, SHAP, Scikit-learn)
- Google Colab
- Plotly (interactive visualizations)

## 📌 Next Steps

- Add weather + aircraft type data
- Improve class balancing in model
- Deploy dashboard with Streamlit or Dash
 
