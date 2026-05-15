# Car Resale Price Prediction & Analysis 🚗📊

## Project Overview

This project focuses on analyzing and predicting used car resale prices using **Data Analysis, Machine Learning, Object-Oriented Programming (OOP), and Power BI Dashboard Visualization**.

The system helps understand how factors such as:

* Selling Price
* Present Price
* Kilometers Driven
* Fuel Type
* Transmission
* Vehicle Age

affect the resale value of cars.

The project includes:

* Exploratory Data Analysis (EDA)
* Data Cleaning & Visualization
* OOP Concepts in Python
* Machine Learning Prediction Models
* Interactive Power BI Dashboard

---

# Technologies Used 🛠️

## Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Dashboard & Visualization

* Power BI

## Machine Learning Models

* Linear Regression
* Random Forest Regressor

---

# Project Structure 📂

```text
Car-Resale-Price-Prediction
│
├── CarResaleBI.pbix
├── CarResaleEDA.ipynb
├── MLCarResale.ipynb
├── README.md
├── Screenshot 2026-05-15 224606.png
├── Screenshot 2026-05-15 224653.png
└── daTA.csv

```

---

# Exploratory Data Analysis (EDA) 📈

The dataset was analyzed to identify important patterns and relationships between different car features and resale prices.

### EDA Includes:

✔ Data Cleaning
✔ Missing Value Handling
✔ Feature Analysis
✔ Correlation Analysis
✔ Visualization using Graphs & Charts
✔ OOP-based Python Implementation

---

# Dashboard Features 📊

The interactive Power BI dashboard provides:

* Average Selling Price
* Average Kilometers Driven
* Average Vehicle Age
* Transmission Distribution
* Fuel Type Analysis
* Selling Price Distribution
* Top Car Brands by Average Value
* Interactive Filters & Slicers

---

# Dashboard Preview 🖥️

## Main Dashboard

![Dashboard](dashboard_main.png)

---

## Filtered Dashboard

![Dashboard](dashboard_filtered.png)

# Machine Learning Models 🤖

## 1. Linear Regression Model

### Performance Metrics

| Metric                         | Value  |
| ------------------------------ | ------ |
| Mean Absolute Error (MAE)      | 1.2162 |
| Mean Squared Error (MSE)       | 3.4788 |
| Root Mean Squared Error (RMSE) | 1.8651 |
| R² Score                       | 0.8489 |

### Observation

Linear Regression provides decent predictions but struggles with some complex relationships in the dataset.

---

## 2. Random Forest Regressor

### Performance Metrics

| Metric                         | Value  |
| ------------------------------ | ------ |
| Mean Absolute Error (MAE)      | 0.6387 |
| Mean Squared Error (MSE)       | 0.9215 |
| Root Mean Squared Error (RMSE) | 0.9599 |
| R² Score                       | 0.9599 |

### Observation

Random Forest performed significantly better with:

* Higher accuracy
* Lower prediction errors
* Better handling of non-linear relationships

---

# Best Performing Model 🏆

## Random Forest Regressor

The Random Forest model achieved the best performance with an **R² Score of 0.9599**, making it the most accurate model for predicting car resale prices in this project.

---

# Key Insights 🔍

* Petrol cars dominate the dataset.
* Selling price strongly depends on present price.
* Older vehicles generally have lower resale value.
* Kilometers driven negatively impacts selling price.
* Random Forest outperformed Linear Regression.

---

# Future Improvements 🚀

* Deploy ML model using Flask or Streamlit
* Add real-time price prediction
* Improve dashboard interactivity
* Add more advanced ML algorithms
* Build web-based prediction system

---

# Learning Outcomes 📚

Through this project, I learned:

* Data Cleaning & Visualization
* Exploratory Data Analysis
* Object-Oriented Programming in Python
* Machine Learning Model Building
* Model Evaluation Techniques
* Dashboard Design using Power BI

---


---

# Project Status ✅

✔ Completed
✔ Dashboard Created
✔ ML Models Evaluated
✔ Ready for Portfolio & Resume Use
