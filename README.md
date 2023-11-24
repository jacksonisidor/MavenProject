# The Maven Project
NSF-awarded research addressing global vaccination trends and factors influencing vaccine uptake for common diseases

## Project Goal
Implement data science and analytical techniques to answer 2 main questions:
Q1) What are the structural, social, and individual factors related to vaccine uptake for common diseases (e.g., influenza), newer pandemics/epidemics, e.g., COVID-19, mpox (monkeypox), and future diseases? 
Q2) How does population heterogeneity affect vaccination behavior in a community context? 

## Overview
This repository contains my personal work contributed to the Maven Project, as well as the team's conclusive report. Employing a variety of methods and tools, I primarily utilized Python and SQL for data processing, cleaning, and analysis. The culmination of these steps lead to the construction of an ARIMAX model incorporating exogenous variables to forecast vaccination trends, optimizing predictive accuracy over several months. 

## Data Source
@article{Wahltinez2020,
  author = "O. Wahltinez and others",
  year = 2020,
  title = "COVID-19 Open-Data: curating a fine-grained, global-scale data repository for SARS-CoV-2",
  note = "Work in progress",
  url = {https://goo.gle/covid-19-open-data},
}

## Project Structure
  - `maven_processing.ipynb`: A Jupyter Notebook cleaning, processing, and analyzing COVID-19 data.
  - `Vaccination_ARIMAX.ipynb`: A Jupyter Notebook containing all the steps to develop a robust ARIMAX model with an interpretation and recommendation of use.
  - `MavenReport.pdf`: My team's conclusive report outlining our findings in LaTeX formatting. 
