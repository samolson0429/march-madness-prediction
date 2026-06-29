# March Madness Prediction

## Predicting March Madness Success Using KenPom Analytics

<img width="416" height="278" alt="image" src="https://github.com/user-attachments/assets/5e74763d-9ea0-4256-a189-06119455acaf" />


## Overview

This project investigates whether KenPom's "Four Factors" statistics can predict NCAA Tournament success.

Using data from the 2014-2024 NCAA tournaments (excluding 2020), I built a linear regression model to estimate the number of tournament games each team would win and identify which team characteristics are most strongly associated with postseason success.

The repository is centered around a Jupyter Notebook that documents the complete analytical workflow-from data loading and exploratory analysis through model development, evaluation, and interpretation.

## Research Questions

1. How accurately can KenPom's Four Factors predict NCAA Tournament performance?

2. Which offensive and defensive factors contribute most to tournament success?

## Tools Used

- Python
- pandas
- matplotlib
- scikit-learn
- statsmodels

## Analytical Techniques

- Data Cleaning
- Exploratory Data Analysis
- Linear Regression
- Model Evaluation
- Prediction
- Feature Importance (the image at the top of this README demonstrates the feature importance analysis)

## Methodology

- Import, integrate, and clean publicly available datasets from KenPom
- Conduct exploratory data analysis
- Build a linear regression model and evaluate the model summary
- Use the model to make predictions on test data
- Conduct a feature importance analysis

## Repository Contents

- march_madness_prediction.ipynb: Jupyter Notebook containing the full analysis, visualizations, and modeling workflow
- data folder: KenPom datasets used in the analysis

## Dataset

- Publicly available KenPom statistics
- 2014-2024 NCAA tournaments
- Eight predictor variables
- Tournament wins used as the response variable
