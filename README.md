# Food Delivery Time Prediction

## Project Overview

This project analyzes the factors that influence food delivery time and compares several statistical and machine learning models for prediction.

The analysis covers the complete workflow from data cleaning and exploratory data analysis to model evaluation and interpretation. The models include:

* Multiple Linear Regression
* Random Forest
* XGBoost

## Dataset

The dataset contains 1,000 food delivery records with variables related to:

* Delivery distance
* Food preparation time
* Weather conditions
* Traffic conditions
* Courier experience
* Vehicle type
* Delivery time

After removing incomplete observations, 970 records were included in the final analysis.

## Methodology

The main steps of the project were:

1. Data cleaning and missing-value assessment
2. Exploratory data analysis and visualization
3. Feature preparation
4. Train-test split using an 80/20 ratio
5. Model development and comparison
6. Model evaluation using RMSE, MAE, and R²
7. Variable importance and partial dependence analysis

## Key Results

The Multiple Linear Regression model achieved the best test-set performance:

| Model             |   RMSE |   MAE |    R² |
| ----------------- | -----: | ----: | ----: |
| Linear Regression | 10.424 | 6.459 | 0.760 |
| Random Forest     | 11.055 |     — | 0.730 |
| XGBoost           | 11.348 |     — | 0.715 |

Delivery distance and food preparation time were identified as the most influential predictors of delivery time.

Although Random Forest and XGBoost can capture nonlinear relationships, the Linear Regression model performed best on this dataset and provided a more interpretable explanation of the main delivery-time drivers.

## Repository Structure

* [`Food_Delivery_Times.csv`](Food_Delivery_Times.csv): Dataset used in the analysis
* [`MA679_Report.pdf`](MA679_Report.pdf): Final project report, including methodology, results, visualizations, and conclusions
* [`final-project-679.pdf`](final-project-679.pdf): Rendered R analysis and code output

## Tools and Techniques

* R
* Data cleaning and exploratory data analysis
* Multiple Linear Regression
* Random Forest
* XGBoost
* Model evaluation
* Variable importance
* Partial dependence plots
* Data visualization

## Potential Business Applications

The results can help food delivery platforms:

* Identify the main causes of delivery delays
* Improve delivery-time estimates
* Optimize courier assignment and delivery routing
* Monitor operational performance
* Improve the customer experience

## Author

**Sarah La (苏拉)**
M.S. in Statistical Practice, Boston University
B.S. in Applied Mathematics, University of California, Davis
