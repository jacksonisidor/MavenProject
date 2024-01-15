# The Maven Project
NSF-awarded research addressing global vaccination trends and factors influencing vaccine uptake for common diseases

## Project Goal
Implement data science and analytical techniques to answer 2 main questions:
Q1) What are the structural, social, and individual factors related to vaccine uptake for common diseases (e.g., influenza), newer pandemics/epidemics, e.g., COVID-19, mpox (monkeypox), and future diseases? 
Q2) How does population heterogeneity affect vaccination behavior in a community context? 

## Overview
This repository contains my personal work contributed to the Maven Project, as well as the team's conclusive report. Employing a variety of methods and tools, I primarily utilized Python and SQL for data processing, cleaning, and analysis. The culmination of these steps lead to the construction of an ARIMAX model incorporating exogenous variables to forecast vaccination trends, optimizing predictive accuracy over several months. 

## Summary of Final Model
The final model constructed in this notebook leveraged cross-validation with a nested grid search to optimize parameters on each fold, ensuring robust predictive capabilities. The preprocessing stage involved smoothing both the new daily vaccination data and exogenous variables related to mobility, enabling the capture of essential trends. 

Impressively, the model showcased a high R-squared value of 0.93, indicating a 93% explanation of variance. The Root Mean Squared Error (RMSE) was respectively low, given the scale of actual values. A 95% confidence interval was constructed around the predictions, which was able to encompass the entire range of actual new daily vaccinations. This result showcases the model's reliability and represents a powerful tool for anticipating vaccination trends.

## Data Source
Data citation as provided by Google Health: 

**Wahltinez2020**
- **Author:** O. Wahltinez and others
- **Year:** 2020
- **Title:** COVID-19 Open-Data: curating a fine-grained, global-scale data repository for SARS-CoV-2
- **Note:** Work in progress
- **URL:** [https://goo.gle/covid-19-open-data](https://goo.gle/covid-19-open-data)

## Project Structure
  - `maven_processing.ipynb`: A Jupyter Notebook cleaning, processing, and analyzing COVID-19 data.
  - `COVID_ARIMAX_2.ipynb`: A Jupyter Notebook containing all the steps to develop a robust ARIMAX model with an interpretation and recommendation of use.
  - `MAVEN_Project.pdf`: My team's conclusive report outlining our findings with LaTeX formatting. 
