# 🍔 Food Delivery Time Prediction System

## 📌 Overview
This project provides a robust machine learning solution designed to help food delivery companies predict delivery times more accurately and evaluate driver performance fairly. By analyzing real-world delivery data, this system identifies key logistical bottlenecks and traffic patterns, ultimately improving the customer experience and operational efficiency. 

This project was developed as part of the **Samsung Innovation Campus (SIC)**.

## ✨ Key Features & Workflow

### 1. Data Processing & Feature Engineering
* **Data Cleaning:** Handled missing values, removed outliers, and corrected data types.
* **Feature Extraction:** Extracted day, month, year, and time of day from order timestamps.
* **Distance Calculation:** Computed the Haversine distance between restaurant and delivery locations using latitude and longitude coordinates.
* **Categorical Encoding:** Encoded categorical variables such as weather conditions, traffic levels, and vehicle types.

### 2. Exploratory Data Analysis (EDA)
* Analyzed the distribution of delivery times.
* Investigated the correlation between delivery time and external factors (e.g., heavy traffic vs. clear weather).
* Visualized order density across different city zones.

### 3. Machine Learning Pipeline
Tested multiple regression algorithms to identify the most accurate model for predicting delivery duration, including:
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* **XGBoost Regressor (Selected Model)**

### 4. Interactive Visualization
Includes a comprehensive **Power BI Dashboard** to visualize delivery performance, map traffic patterns, and track city-wise trends.

## 🛠️ Tech Stack
* **Languages:** Python
* **Machine Learning:** Scikit-Learn, XGBoost
* **Data Analysis & Processing:** Pandas, NumPy
* **Data Visualization:** Power BI, Matplotlib, Seaborn

## 📊 Model Performance
The chosen XGBoost Regressor yielded highly reliable results for practical deployment:
* **R² Score:** 0.82
* **Average Prediction Error:** ~ 3 minutes

## 🚀 Links & Resources
* **Live Deployment:** [https://food-delivery-time-predictor.streamlit.app/]
* **Kaggle Notebook:** [https://www.kaggle.com/code/mohamedmakram74/predicting-food-delivery-time]

## 🤝 Acknowledgements
Developed collaboratively with Ahmed Kamal and Mahmoud Hamed Ahmed, with valuable guidance from Eng. Ayaa Nada during the Samsung Innovation Campus program.
