# Visit-Riyadh 🌟 Personalized Next POI Recommendation System

## 📌 Overview
The **Personalized Next POI Recommendation System** is designed to predict the next point of interest (POI) a user is likely to visit based on historical check-in data. By analyzing user transitions between venues, the system considers factors such as distance, time, preferences, and check-in history to generate accurate recommendations.

## 📂 Dataset
The dataset consists of **1000 manually collected entries**, containing the following key features:
- `User ID`: Identifies unique users.
- `Latitude` & `Longitude`: Geographic coordinates of visited locations.
- `Check-in Time` & `Day`: Temporal aspects of visits.
- `Previous Venue ID`: The last visited location.
- `Venue Name` & `Venue Category`: Descriptive attributes of the place.
- `Venue ID`: Identifies unique venues.

## 🔄 Data Processing
To ensure data quality and enhance prediction accuracy, the following preprocessing steps are applied:
1. **Data Cleaning**
2. **Standardization of Categorical Variables**
3. **Feature Engineering**
4. **Feature Selection and Optimization**

## 🤖 Model Implementation
The system is built using **a regression-based approach** to predict the location directly. Key steps include:
1. **Model Preparation**
2. **Model Training**
3. **Evaluation**
