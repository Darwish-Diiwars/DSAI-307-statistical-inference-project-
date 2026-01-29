# DSAI_307_Project

## Overview
This project performs an exploratory data analysis (EDA) on a diabetes dataset using R. The dataset includes variables such as Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age, and Outcome (Diabetic or Non-Diabetic). The analysis covers data loading, summary statistics, and specific calculations like average glucose levels by outcome, along with visualizations.

The project is implemented in a Jupyter Notebook (R kernel) and demonstrates basic data manipulation and visualization techniques.

## Dataset
- Source: The dataset is loaded from `diabetes_dataset.csv` (assumed to be in the project directory).
- Key Features:
  - Pregnancies: Number of times pregnant.
  - Glucose: Plasma glucose concentration.
  - BloodPressure: Diastolic blood pressure.
  - SkinThickness: Triceps skin fold thickness.
  - Insulin: 2-Hour serum insulin.
  - BMI: Body mass index.
  - DiabetesPedigreeFunction: Diabetes pedigree function.
  - Age: Age in years.
  - Outcome: Class variable (0 = Non-Diabetic, 1 = Diabetic).

## Requirements
- R (version 4.0+ recommended).
- Jupyter Notebook or RStudio for running the `.ipynb` file.
- Required R Packages (installed in the notebook):
  - tidyverse
  - ggplot2
  - broom
  - GGally
  - NbClust
  - cluster
  - dplyr

Install packages manually if needed:
```r
install.packages(c("tidyverse", "ggplot2", "broom", "GGally", "NbClust", "cluster", "dplyr"))
