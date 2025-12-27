# 🚗 Electric Vehicle (EV) Range Predictor

An end-to-end Machine Learning project that predicts the **Electric Range** of vehicles using the U.S. Government's Open Data. This repository includes the full pipeline: from Exploratory Data Analysis (EDA) to a deployed web interface using **Streamlit**.

## 📌 Project Overview
The goal of this project is to estimate the driving range of an electric vehicle based on its manufacturer (Make), model year, and vehicle type. 

**Key Features:**
* **Data Source:** [Data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data) (Electric Vehicle Population Data).
* **Model:** Random Forest Regressor.
* **Deployment:** Interactive Dashboard built with Streamlit.

## 📊 Exploratory Data Analysis (EDA)
During the analysis phase, we discovered:
* **Yearly Trends:** Average battery range has increased significantly over the last decade.
* **Vehicle Types:** Battery Electric Vehicles (BEVs) show a wider range variance compared to Plug-in Hybrids (PHEVs).
* **Feature Importance:** The car's **Manufacturer (Make)** and **Model Year** are the strongest predictors of its range.
