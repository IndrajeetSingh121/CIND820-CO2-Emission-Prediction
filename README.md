# Predicting Vehicle CO₂ Emissions Using Canadian Vehicle Data

## Project Overview

Transportation is a major contributor to greenhouse gas emissions and environmental sustainability challenges. This project investigates the relationship between vehicle characteristics, fuel consumption, and CO2 emissions using Canadian vehicle fuel consumption data. The objective is to identify the factors associated with higher emissions and develop predictive models capable of estimating vehicle CO2 emissions from vehicle specifications.

## Dataset Source

The dataset used in this project was obtained from the Government of Canada Open Data Portal and is published by Natural Resources Canada (NRCan).

**Dataset Link:**

https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64

The dataset contains fuel consumption ratings and estimated CO2 emissions for new light-duty vehicles sold in Canada between model years 2015 and 2024. Variables include vehicle specifications, fuel consumption measures, environmental ratings, and CO2 emissions.

Dataset Size

- 10,060 observations
- 15 variables
- Model Years: 2015–2024

## Project Objectives

This project aims to:

• Predict vehicle CO₂ emissions using vehicle characteristics.
• Identify the factors associated with higher vehicle emissions.
• Compare the performance of Multiple Linear Regression and Random Forest Regression models.
• Support transportation sustainability analysis through predictive modelling.

## Planned Approach

### Step 1: Data Loading and Exploratory Data Analysis (EDA)
Load the Canadian fuel consumption dataset and perform descriptive analysis to understand the dataset structure, variable distributions, missing values, outliers, and relationships between vehicle characteristics and CO₂ emissions.

### Step 2: Train-Test Split
Split the dataset into training (80%) and testing (20%) sets before any preprocessing. This prevents information from the testing data from influencing model training and reduces the risk of data leakage.

### Step 3: Data Preprocessing
Handle missing values using median imputation, transform categorical variables using one-hot encoding, and standardize numerical variables. All fitted transformations are learned from the training data and then applied to the testing data.

### Step 4: Model Development
Develop baseline predictive models using Multiple Linear Regression and Random Forest Regression to estimate vehicle CO₂ emissions.

### Step 5: Model Evaluation
Evaluate model performance using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score. Compare the performance of both models.

### Step 6: Model Validation
Assess the modelling pipeline through residual diagnostics, overfitting assessment, and proxy leakage evaluation to ensure reliable model performance.

### Step 7: Results and Interpretation
Interpret the modelling results, compare model performance, and identify the vehicle characteristics most strongly associated with CO₂ emissions.

## Repository Structure

* **Dataset** – Original dataset used in the project.
* **Notebooks** – Google Colab notebooks used for analysis and modelling.
* **EDA Reports** – Generated exploratory data analysis and profiling reports.
* **Figures** – Project figures, visualizations, and system architecture diagrams.
* **Final Report** – Final project report and supporting deliverables.

## Environment and Required Dependencies

The project was developed using **Python in Google Colab**. The following libraries are required to reproduce the analysis:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy
* ydata-profiling


## Project Artifacts

- EDA Notebook: [CIND_820_EDA.ipynb](./Notebooks/CIND_820_EDA.ipynb)

- Generated EDA Report: [Final_EDA_820.html](./EDA%20Reports/Final_EDA_820.html)
### Model Development Notebook

* Project Notebook (.ipynb):

### Compiled Model Development Notebook

* HTML Version: 

* Final Report: Final project report (to be added upon completion)

## Expected Outputs

Running the notebook will generate the following outputs:

* Descriptive statistics
* Histograms and boxplots
* Scatter plots
* Preprocessed training and testing datasets
* Multiple Linear Regression performance metrics
* Random Forest Regression performance metrics
* Residual diagnostic plots
* Model comparison table
* HTML Exploratory Data Analysis report

### Coding Assistance Declaration

All code submitted in this project was developed, tested, and validated by me. I take full responsibility for the design, implementation, and correctness of the code and the results it produces.

## Conclusion

This repository documents the development of a predictive analytics project focused on vehicle fuel consumption and CO2 emissions in Canada. Through data profiling, preprocessing, feature engineering, and predictive modelling, the project aims to improve understanding of the factors associated with vehicle emissions and evaluate the effectiveness of different modelling approaches for emissions prediction.

