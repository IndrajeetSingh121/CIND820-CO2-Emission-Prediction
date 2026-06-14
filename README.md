# Predicting Vehicle CO₂ Emissions Using Canadian Vehicle Data

## Project Overview

Transportation is a major contributor to greenhouse gas emissions and environmental sustainability challenges. This project investigates the relationship between vehicle characteristics, fuel consumption, and CO2 emissions using Canadian vehicle fuel consumption data. The objective is to identify the factors associated with higher emissions and develop predictive models capable of estimating vehicle CO2 emissions from vehicle specifications.

## Dataset Source

The dataset used in this project was obtained from the Government of Canada Open Data Portal and is published by Natural Resources Canada (NRCan).

**Dataset Link:**

https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64

The dataset contains fuel consumption ratings and estimated CO2 emissions for new light-duty vehicles sold in Canada between model years 2015 and 2024. Variables include vehicle specifications, fuel consumption measures, environmental ratings, and CO2 emissions.

## Planned Approach

The project follows the analytical workflow below:

### Step 1: Data Profiling and Exploratory Data Analysis (EDA)

Examine the dataset structure, assess data quality, identify missing values and outliers, and explore relationships between vehicle characteristics, fuel consumption, and CO2 emissions.

### Step 2: Data Preprocessing

Prepare the dataset for analysis by addressing missing values through imputation, validating data types, checking for duplicate records, and assessing data consistency.

### Step 3: Feature Engineering

Select relevant predictor variables and transform categorical variables into machine-learning-ready features using one-hot encoding.

### Step 4: Model Development

Develop and compare Linear Regression and Random Forest Regression models for predicting vehicle CO2 emissions.

### Step 5: Model Evaluation

Evaluate model performance using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.

### Step 6: Results and Interpretation

Compare model performance and identify the vehicle characteristics most strongly associated with vehicle CO2 emissions.

## Repository Structure

* **Dataset** – Original dataset used in the project.
* **Notebooks** – Google Colab notebooks used for analysis and modelling.
* **EDA Reports** – Generated exploratory data analysis and profiling reports.
* **Figures** – Project figures, visualizations, and system architecture diagrams.
* **Final Report** – Final project report and supporting deliverables.
### Key Project Files

- EDA Notebook: [CIND_820_EDA.ipynb](./Notebooks/CIND_820_EDA.ipynb)

- Generated EDA Report: [Final_EDA_820.html](./EDA%20Reports/Final_EDA_820.html)
## Conclusion

This repository documents the development of a predictive analytics project focused on vehicle fuel consumption and CO2 emissions in Canada. Through data profiling, preprocessing, feature engineering, and predictive modelling, the project aims to improve understanding of the factors associated with vehicle emissions and evaluate the effectiveness of different modelling approaches for emissions prediction.

