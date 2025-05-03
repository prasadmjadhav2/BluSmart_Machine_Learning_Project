# ⚡ BluSmart ML Project: Powering India’s EV Rides with Predictive Intelligence ⚡

[![BluSmart](https://static.thearcweb.com/images/PROD/PROD-1726cf5e-1636-4240-b1ff-cfab53bf6457.png)

This repository showcases my latest machine learning project with BluSmart, where data science was leveraged to optimize electric vehicle (EV) ride operations, forecast demand, and ensure sustainable, data-driven urban mobility in India.

## 📍 Project Highlights:

- **Dataset:** 10,000 records with 20 rich features.
- **Scope:** Encompassed ride demand forecasting, driver performance evaluation, battery usage prediction, vehicle maintenance anticipation, and fare optimization.
- **Goal:** To build intelligent systems that drive cleaner, smarter urban mobility.

## 🚀 Major ML Solutions & Achievements:

### 1️⃣ Ride Demand Forecasting (Time Series)
- **Models:** NeuralProphet, ARIMA, and LSTM.
- **Objective:** To accurately model hourly ride demand for smarter scheduling.
- **Achievement:** Forecasted demand spikes with an **RMSE of ~33.1**.

### 2️⃣ Driver Performance Classification
- **Model:** Random Forest Classifier.
- **Objective:** To classify drivers as "good" or "needs attention" based on performance metrics.
- **Achievement:** Achieved an **accuracy of 70.1%** using ride metrics, fare, and distance data.

### 3️⃣ Ride Cancellation Prediction
- **Model:** XGBoost Classifier.
- **Objective:** To predict ride cancellations to minimize disruptions.
- **Achievement:** Reached an **accuracy of 89.9%** by leveraging weather, traffic, and scheduling data.

### 4️⃣ Vehicle Maintenance Prediction
- **Model:** Gradient Boosting Classifier.
- **Objective:** To predict post-ride service needs proactively.
- **Technique:** Addressed class imbalance using **SMOTE**, enhancing recall for maintenance-prone rides.

### 5️⃣ Fare Prediction Model
- **Model:** Linear Regression.
- **Objective:** To enable dynamic pricing based on various factors.
- **Achievement:** Trained a model with an **extremely low Mean Squared Error (MSE)**, factoring in ride conditions and route data.

### 6️⃣ Battery Level Forecasting
- **Model:** Decision Tree Regressor.
- **Objective:** To predict the battery level of EVs post-ride for range and recharge optimization.
- **Achievement:** Achieved a **Mean Absolute Error (MAE) of 27.15**.

## 🔍 Advanced Features Engineered:

- Integrated **traffic and weather insights** into the models.
- Incorporated **proximity to charging stations** as a relevant feature.
- Implemented **time-based demand segmentation** (peak vs. off-peak hours).
- Applied **encoding techniques** for categorical variables like vehicle models and payment methods to improve model learning.

## ♻️ Impact:

This project contributes to:

- **Boosted ride reliability** and improved **driver quality**.
- Supported **carbon-conscious decision-making** through optimized EV usage.
- Enabled **proactive fleet and battery management**, leading to operational efficiency.

## 🛠️ Technologies Used:

- Python
- Machine Learning Libraries (scikit-learn, TensorFlow/Keras, XGBoost, NeuralProphet)
- Data Analysis Libraries (Pandas, NumPy)
- Data Visualization Libraries (Matplotlib, Seaborn - *mention if used*)

## 🚀 Next Steps (Optional):

- Further exploration of deep learning models for time series forecasting.
- Implementing real-time data pipelines for dynamic predictions.
- Developing a user interface for visualizing the model outputs and insights.

## 🤝 Let's Connect!

I'm passionate about the intersection of mobility, machine learning, and EV technology. Feel free to connect if you have similar interests or would like to discuss this project further!
