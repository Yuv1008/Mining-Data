# Predicting Calories Burned During Workouts

A data science project that explores what drives calorie burn during exercise
and builds a model to predict it from workout and body metrics.

Built for COMP 381 (Data Science Engineering) at the University of the Fraser Valley.

## Overview

The goal was to answer one question: which factors most affect how many calories
you burn in a workout, and can we predict it accurately? Using data from 973 gym
members, we explored the data, compared two models, and turned the results into
clear, practical takeaways.

## Key Findings

- Workout length (session duration) is by far the strongest driver of calories burned
- Heart rate, training frequency, and experience level come next
- Workout type (Strength, Cardio, Yoga, HIIT) has surprisingly little effect
- Linear Regression predicted calories burned with about 98% accuracy (R² ≈ 0.98),
  beating the more complex Neural Network

The takeaway: when the relationship in the data is mostly linear, a simple,
interpretable model can outperform a more complex one.

## Dataset

[Gym Members Exercise Dataset](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset)
from Kaggle — 973 members, 15 features including age, gender, body metrics,
heart rate, session duration, workout type, and calories burned.

## Tools

- Python
- pandas, NumPy
- scikit-learn (Linear Regression, Neural Network)
- Matplotlib, Seaborn
- Jupyter Notebook

## Method

1. Load and clean the data (no missing values or duplicates)
2. Exploratory data analysis with visualizations
3. One-hot encode categorical features and scale numeric ones
4. Train/test split (80/20)
5. Train and compare Linear Regression and a Neural Network using R², RMSE, and MAE

## Files

- `Gym_Calorie_Analysis.ipynb` — full analysis notebook
- `gym_members_exercise_tracking.csv` — dataset
- `Report.docx` — written report
- `Presentation.pptx` — slide deck

## Authors

Yuvraj Singh Goraya and Navpreet Singh
