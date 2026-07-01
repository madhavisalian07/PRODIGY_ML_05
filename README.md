# PRODIGY_ML_05
# Food Recognition and Calorie Estimation Model

This repository contains the implementation of a Food Recognition and Calorie Estimation framework developed as part of Task 5 during my Machine Learning internship at Prodigy InfoTech.

## Project Overview
This project builds an automated machine learning pipeline that identifies food items from simulated image features and estimates their calorie content, enabling users to track their dietary intake and make informed food choices.

## Implementation Steps
1. **Data Generation & Mapping**: Created a synthetic dataset of 1,000 food image feature matrices spanning 4 distinct food categories: Pizza, Burger, Salad, and Apple. Integrated an exact calorie lookup dictionary mapping each item to its respective energy value (kcal).
2. **Data Splitting**: Divided the dataset into an 80/20 train-test ratio using stratified sampling to maintain balanced dietary distributions across splits.
3. **Model Construction**: Utilized a `RandomForestClassifier` architecture to handle the multi-class visual identification task.
4. **Training**: Trained the ensemble model on the feature subsets to optimize split decisions and boost prediction confidence.
5. **Evaluation & Tracking**: Evaluated the classification performance using accuracy metrics, and successfully simulated a dietary tracking interface displaying detected food items alongside their estimated calorie output.

## Tech Stack
* Python
* Scikit-Learn
* NumPy
