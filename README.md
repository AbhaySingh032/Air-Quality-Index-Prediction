# 🌫️ Air Quality Index (AQI) Prediction – Indian Cities

This repository contains a detailed machine learning project aimed at predicting the Air Quality Index (AQI) using 5 years of air pollution data from multiple Indian cities, available at both hourly and daily granularity. The project explores the temporal trends, pollutant impacts, and predictive modeling for both AQI values and categories.


# 📁 Dataset Description
Source: Indian city pollution datasets (hourly and daily granularity)

Duration: 2015–2020 (~5 years)

Cities: Covers major Indian metro and tier-2 cities

**Files:**

city_day.csv: Daily average pollution data

city_hour.csv: Hourly pollution data


# 🔑 Key Columns:

PM2.5, PM10, NO₂, SO₂, CO, O₃, NH₃, AQI, AQI_Bucket

City, Date or Datetime

AQI Bucket values include: Good, Satisfactory, Moderate, Poor, Very Poor, Severe


# 📊 Notebooks Overview

**📘 city_day.ipynb**

Handles city_day.csv dataset

Daily-level trends and AQI predictions

Includes seasonal and yearly variations

Trains regression and classification models

**📘 city_hour.ipynb**

Handles city_hour.csv dataset

Fine-grained hourly analysis

Detects intra-day pollutant fluctuations

Real-time AQI prediction modeling

# 🎯 Objectives

🔍 Perform EDA to identify pollution trends across cities and seasons

🛠️ Clean, preprocess, and impute missing data

🧠 Train machine learning models to predict:

AQI (as a regression task)

AQI Bucket (as a classification task)

📈 Visualize pollution patterns, pollutant correlations, and model performance


# 🤖 Machine Learning Models Used

Linear Regression

Random Forest Regressor & Classifier

XGBoost Regressor & Classifier

Decision Tree

Logistic Regression

Support Vector Machines


# 📈 Visualizations & Insights

📌 City-wise AQI distribution over time

📌 Heatmaps of pollutant correlation

📌 AQI category breakdown per city

📌 Feature importance charts

📌 Prediction vs. Actual AQI plots


# 🚀 How to Run

**Clone the repository**

git clone https://github.com/AbhaySingh032/Air-Quality-Index-Prediction

cd Air-Quality-Index-Prediction

**Install required libraries**

pip install -r requirements.txt

**Launch analysis notebooks**

jupyter notebook notebooks/city_day.ipynb

jupyter notebook notebooks/city_hour.ipynb


# 📂 Folder Structure

Air-Quality-Index-Prediction/

├── data/
│   ├── city_day.csv
│   └── city_hour.csv

├── notebooks/
│   ├── city_day.ipynb
│   └── city_hour.ipynb

├── models/
│   └── saved_model.pkl

├── outputs/
│   └── charts/ (generated plots)

├── README.md

└── requirements.txt


# 🧰 Tools & Libraries

Python – Data processing & modeling

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Scikit-learn, XGBoost – ML modeling

Jupyter Notebook – Interactive exploration


# 📬 Author

Abhay Pal Singh

📧 rabhay032@gmail.com


# ⭐ Support

If this project helped you or you found it interesting, feel free to ⭐ the repository and share your feedback!

