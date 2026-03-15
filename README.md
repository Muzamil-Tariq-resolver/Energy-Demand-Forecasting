# Smart Energy Consumption Forecasting System

## 📊 Project Overview

This project is an end-to-end **Energy Consumption Forecasting System** that integrates:

- Machine Learning
- Weather Data Analysis
- Database Management
- API Integration
- Workflow Automation
- Business Intelligence Dashboard

The system predicts building energy consumption (meter reading in kWh) using historical data and environmental features.

---

## 🎯 Objective

To build a predictive model that estimates future energy usage of buildings based on:

- Building characteristics
- Weather conditions
- Time-based features

This project demonstrates a complete data pipeline from data collection to visualization.

---

## 🛠 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- MySQL
- Apache Airflow
- OpenWeather API
- Tableau
- Matplotlib / Seaborn

---

## 📂 Dataset Description

The dataset contains building metadata, weather information, and energy consumption records.

### 🔹 Target Variable

- **meter_reading** → Energy consumption (kWh)

---

## 📌 Features (Input Variables)

### 🏢 Building Information

- **building_id** → Foreign key for building metadata  
- **primary_use** → Category of building activity (based on EnergyStar definitions)  
- **square_feet** → Gross floor area of building  
- **year_built** → Year the building was opened  
- **floor_count** → Number of floors  

---

### 🌦 Weather Features

- **timestamp** → Time of measurement  
- **air_temperature** → Degrees Celsius  
- **cloud_coverage** → Sky coverage in oktas  
- **dew_temperature** → Degrees Celsius  
- **precip_depth_1_hr** → Rainfall in millimeters  
- **sea_level_pressure** → Millibar / hectopascals  
- **wind_direction** → Compass direction (0–360 degrees)  
- **wind_speed** → Meters per second  

---

## 🧠 Machine Learning Approach

The project includes:

- Data cleaning
- Feature engineering
- Time-series preprocessing
- Model training
- Performance evaluation

### Models Used:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting
- (Optional) LSTM for advanced forecasting

### Evaluation Metrics:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 🔄 System Architecture

Data Pipeline:

1. Historical dataset (training)
2. Weather API integration
3. Data stored in MySQL
4. Model training
5. Prediction generation
6. Visualization in Tableau

---

## 📊 Dashboard

The project includes an interactive **Tableau dashboard** showing:

- Energy consumption trends
- Predicted vs Actual values
- Weather impact analysis
- Peak demand hours
- Building-wise comparison

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
