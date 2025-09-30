# Student Grade Prediction Using Regression

## Project Overview
- This project applies regression analysis to predict students' final grade(G3) based on two factors:
  - Weekly Study Time (X1) using a 1-4 scale
  - Number of school absences (X2) from 0 - 93
- This project demonstrates how effort and engagement affect academic success by modeling the relationship between study habits, attendance, and performance.
- The dataset comes from the UCI Machine Learning Repository.

## Variables
- Target(Y): G3 - Final grade(continous variable)
- Predictor (X1, X2): 
  - studytime - Weekly study time (1–4, categorical), reflects the student's academic effort and preparation
  - absences - Number of school absences (continuous, 0–93), reflects disengagement and missed learning

## Why This is a Good Model
This regression model predicts a student's final grade (G3) using study time and absences.
Higher study time is associated with better grades, while absences may reduce them. The model demonstrates how educational data, like study time and absences, can be used to understand and forecast student performance.

Assignment5.ipynb is my Colab code.
student-mat.csv is the dataset I used to make the regression model.
