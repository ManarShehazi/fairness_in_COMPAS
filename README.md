# Fairness in Classification on the COMPAS Dataset

## Overview

This project involves analyzing fairness in classification using the **COMPAS** dataset, which includes information about criminal defendants in Broward County, Florida, screened for recidivism risk. The COMPAS risk assessment tool has been shown to exhibit bias against certain demographic groups, and this project explores those biases, builds classifiers to predict recidivism, and attempts to create a fairer model. The project was completed in April 2024 as part of the **Foundations of Data Science** course.

## Project Goals

1. **Bias Analysis**: Analyze the COMPAS dataset to identify biases, especially those related to race and gender.
2. **Standard Classifiers**: Train multiple classifiers to predict recidivism and evaluate their fairness relative to COMPAS.
3. **Fair Classifier**: Implement a classifier that incorporates a fairness notion and compare its performance and fairness to standard classifiers.

## Dataset

The **COMPAS dataset** includes demographic information, criminal history, and recidivism risk scores for defendants. Key fields include:
- **Demographic Information**: Gender, race, etc.
- **Criminal History**: Prior offenses, case details.
- **COMPAS Scores**: Risk rating (1-10) and categorization into low, medium, or high risk.
- **Recidivism Outcome**: Whether the defendant re-offended within two years.

Link to dataset: [compas-scores-two-years.csv on GitHub](https://github.com/propublica/compas-analysis).

## Features

- **Dataset Exploration**: Conduct a descriptive analysis of the dataset, covering feature distributions, label distributions, and demographic breakdowns.
- **Bias Detection**: Calculate performance metrics for the COMPAS classifier across different demographic groups (e.g., racial and gender differences).
- **Standard Classification Models**:
  - Train and evaluate multiple classifiers (e.g., logistic regression, decision trees, SVM) to predict recidivism.
  - Compare classifier performance to COMPAS and analyze their fairness.
  - Define and evaluate fairness metrics for each classifier.
- **Fair Classifier Implementation**:
  - Explore methods to create fair classifiers, such as excluding race from features or applying fairness constraints.
  - Implement a fair classifier and compare its performance and fairness to other models.

## Technologies Used

- **Programming Language**: Python
- **Jupyter Notebook**: For code, analyses, and visualizations
- **Libraries**: 
  - **pandas** and **numpy** for data manipulation
  - **scikit-learn** for machine learning models
  - **matplotlib** and **seaborn** for visualizations

## Project Structure

