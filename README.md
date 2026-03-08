# House Price Prediction using Machine Learning

## Project Overview

This project aims to predict housing prices in California using machine learning techniques.
The dataset contains information about housing features such as income, population, location, and housing characteristics.

The goal of this project is to perform **data analysis, feature engineering, and regression modeling** to accurately predict house prices.

---

## Dataset

The dataset used in this project is the **California Housing Dataset**.

Features include:

* Median income
* Housing median age
* Total rooms
* Total bedrooms
* Population
* Households
* Latitude
* Longitude

Target variable:

* **Median House Value**

---

## Project Workflow

1. Data Loading
2. Data Understanding
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Feature Selection
7. Model Training
8. Model Comparison
9. Model Evaluation

---

## Feature Engineering

New features were created to improve model performance:

* `rooms_per_household`
* `bedrooms_per_room`
* `population_per_household`

These engineered features help capture **household-level characteristics** that influence housing prices.

---

## Models Used

The following regression models were trained and compared:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

---

## Model Performance

The final model used **Random Forest Regressor**, achieving approximately:

**R² Score ≈ 0.80**

This means the model explains around **80% of the variance in housing prices**.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

house-price-prediction
│
├── data
│   └── housing.csv
│
├── notebook
│   └── price_analysis.ipynb
│
└── README.md

---

## Author

Shanmuk Reddy
