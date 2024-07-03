# Diabetes Prediction Using Machine Learning

This Data Science Capstone Project aims to build a model to accurately predict whether the patients in the dataset have diabetes or not using Python and Tableau 10. The dataset, originally from NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases), consists of several medical predictor variables and one target variable (Outcome).

## Problem Statement
The objective is to predict whether or not a patient has diabetes based on certain diagnostic measurements included in the dataset.

![Dataset Image](https://user-images.githubusercontent.com/110838853/192422423-dea8e137-d476-4b4c-9c57-b93e47e445c5.png)

## Dataset Description
The dataset includes the following variables:
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skinfold thickness (mm)
- Insulin:Two-hour serum insulin
- BMI: Body Mass Index
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age:Age in years
- Outcome: Class variable (either 0 or 1)

## Project Tasks
1. Data Exploration:
   - Perform descriptive analysis to understand the variables and their values. Identify and treat missing values in Glucose, BloodPressure, SkinThickness, Insulin, and BMI.
   - Visually explore these variables using histograms.
   - Check the balance of the data by plotting the count of outcomes. Describe findings and plan future actions.
   - Create scatter charts between pairs of variables to understand relationships.
   - Perform correlation analysis and visualize it using a heat map.

2. Data Modeling:
   - Devise strategies for model building, including deciding the right validation framework.
   - Apply an appropriate classification algorithm to build a model. Compare various models with results from the KNN algorithm.
   - Create a classification report analyzing sensitivity, specificity, and AUC (ROC curve). Explain the chosen parameter values.

3. Data Reporting:
   - Create a Tableau dashboard with the following:
     - Pie chart to describe the diabetic or non-diabetic population
     - Scatter charts between relevant variables to analyze relationships
     - Histogram or frequency charts to analyze data distribution
     - Heatmap of correlation analysis among relevant variables
     - Bubble chart analyzing different variables for age brackets (20-25, 25-30, 30-35, etc.)

![Tableau Dashboard](https://user-images.githubusercontent.com/110838853/192419316-73c8cbc9-5d86-4be0-8cbe-b8430a1538b3.png) 
