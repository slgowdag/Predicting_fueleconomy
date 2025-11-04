
# Predicting Fuel Economy: A Regression-Based Analysis

 🎯 Objective 

The goal of this project is to develop a regression model to predict the fuel efficiency (miles per gallon - MPG) of cars based on various automobile characteristics such as weight, horsepower, displacement, acceleration, and model year. By analyzing historical automotive data, we aim to identify the key factors influencing fuel economy and build a robust predictive model.


 📊 Dataset Overview

The dataset used in this project is the Auto MPG dataset, which contains information on 398 cars sold in the United States during the 1970s and 1980s. It includes various technical specifications of cars along with their fuel efficiency (mpg).

Features in the Dataset

* **mpg (Target Variable):** Fuel efficiency measured in miles per gallon.
* **cylinders:** Number of cylinders in the engine.
* **displacement:** Engine displacement (in cubic inches).
* **horsepower:** Horsepower of the car’s engine.
* **weight:** Weight of the car (in pounds).
* **acceleration:** Time taken to accelerate from 0 to 60 mph (in seconds).
* **model year:** Year in which the car was manufactured.
* **origin:** Country of manufacture (USA, Europe, Japan).
* **car name:** Name of the car model (not used in modeling).



🔬 Methodology

The project follows a structured data science workflow, including:

* **Data Preparation**
    * Load and clean the dataset.
    * Convert categorical features and handle missing values.
* **Exploratory Data Analysis (EDA)**
    * Summary statistics, visualizations, and correlation analysis.
    * Understanding feature-target relationships.
* **Model Development & Evaluation**
    * Train-test split and feature engineering.
    * Fit Linear Regression and Ridge Regression models.
    * Use cross-validation to evaluate performance.
* **Model Selection & Insights**
    * Compare model performance using R² and Mean Absolute Error (MAE).
    * Determine the best model for predicting fuel efficiency.

 📈 Summary of Findings

* Weight, horsepower, and displacement are highly correlated with fuel efficiency (MPG).
* Cars manufactured in Japan tend to have better fuel economy compared to American cars.
* Linear Regression performed well, explaining ~90.4% of the variance in MPG.
* Ridge Regression did not significantly improve the model, so we opted for the OLS model.
