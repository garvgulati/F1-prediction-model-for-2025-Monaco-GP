# 🏎️ F1 Prediction Model – Monaco GP 2025

This project uses machine learning and motorsport analytics to predict the 2025 Monaco Grand Prix race results based on driver performance, weather, and team metrics.

## 🔧 Tech Stack & Tools

- **Python 3.13**
- **FastF1** – for accessing official Formula 1 session and telemetry data  
- **OpenWeatherMap API** – for real-time weather forecasting  
- **pandas / numpy** – for data wrangling and numerical processing  
- **scikit-learn** – for model training (Gradient Boosting Regressor), imputation, and evaluation  
- **matplotlib** – for plotting insights like feature importance and pace effect  
- **Requests** – to fetch external weather data

## 📊 Features Used

- Clean air race pace, qualifying time, sector times  
- Constructor performance score (team strength)  
- Rain probability and temperature at race time  
- Historical position change data at Monaco

## 📈 Output

- Predicted race times per driver  
- Visualizations for insights  
- Podium prediction (Top 3 finishers)

## 📁 Setup

Make sure to install dependencies and add your OpenWeatherMap API key in the script.

