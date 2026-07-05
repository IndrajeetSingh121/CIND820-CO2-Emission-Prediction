# Vehicle CO₂ Emissions Prediction Using Canadian Fuel Consumption Data

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

## Project Workflow

### Step 1: Data Loading and Exploratory Data Analysis (EDA)
The dataset was loaded into Python and explored using descriptive statistics and visualizations. This step was used to understand the dataset structure, identify missing values, detect outliers, and examine relationships between vehicle characteristics and CO₂ emissions.

### Step 2: Train-Test Split
The dataset was divided into 80% training data and 20% testing data before any preprocessing. This helped prevent data leakage and ensured a fair evaluation of model performance.

### Step 3: Data Preprocessing
Missing values were handled using median imputation, categorical variables were transformed using one-hot encoding, and numerical variables were standardized. These preprocessing steps prepared the data for machine learning models.

### Step 4: Model Development
Two regression models, Multiple Linear Regression and Random Forest Regression, were developed to predict vehicle CO₂ emissions. Multiple Linear Regression was used as the baseline model, while Random Forest Regression was used for comparison.

### Step 5: Model Evaluation
The models were evaluated using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score. These metrics were used to compare prediction accuracy and overall model performance.

### Step 6: Model Validation
Additional validation was performed using residual diagnostics, overfitting assessment, and proxy leakage assessment. These checks helped evaluate the reliability and generalization of the models.

### Step 7: Results Interpretation
The results were interpreted by comparing the performance of both models and identifying their strengths and limitations. The findings were used to assess the effectiveness of the proposed modelling approach.

## Repository Structure

* **Dataset** – Original dataset used in the project.
* **Notebooks** – Google Colab notebooks used for analysis and modelling.
* **EDA Reports** – Generated exploratory data analysis and profiling reports.
* **Figures** – Project figures, visualizations, and system architecture diagrams.
* **Final Report** – Final project report and supporting deliverables.

## Environment and Required Dependencies

The project was developed using **Python in Google Colab**. The following libraries are required to reproduce the analysis:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy
- statsmodels
- ydata-profiling

## How to Run the Project

1. Download this repository from GitHub.
2. Open the project notebook in Google Colab or Jupyter Notebook.
3. Locate the dataset in the **Dataset** folder.
4. If using Google Colab, upload the dataset before running the notebook.
5. Install the required Python libraries if they are not already installed.
6. Run all notebook cells from top to bottom to reproduce the analysis and model results.

## Project Artifacts

### Exploratory Data Analysis

- EDA Notebook (.ipynb)
- HTML EDA Report

### Model Development

- Milestone 3 Initial Results Notebook (.ipynb)
- HTML Version of the Notebook
  
### Reports

- Milestone 1 Report
- Milestone 2 Report
- Milestone 3 Initial Results Report
  
## Expected Outputs

Running the notebook will generate the following outputs:

- Descriptive statistics
- Histograms and boxplots
- Scatter plots
- Processed training and testing datasets
- Multiple Linear Regression performance metrics
- Random Forest Regression performance metrics
- Actual vs Predicted plots
- Residual diagnostic plots
- Overfitting assessment
- Proxy leakage assessment
- Model comparison table

## Coding Assistance Declaration

All code submitted in this project was developed, tested, and validated by me. I take full responsibility for the design, implementation, and correctness of the code and the results it produces.

## Conclusion

This repository documents the development of a predictive analytics project focused on vehicle fuel consumption and CO2 emissions in Canada. Through data profiling, preprocessing, feature engineering, and predictive modelling, the project aims to improve understanding of the factors associated with vehicle emissions and evaluate the effectiveness of different modelling approaches for emissions prediction.

## Author

**Indrajeet Singh**

TMU Certificate in Data Analytics, Big Data and Predictive Analytics

Toronto Metropolitan University
