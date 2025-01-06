# Titanic-Passengers-survival-predictio
This repository contains my Kaggle project for the Titanic Survival Prediction competition. The goal is to predict whether a passenger survived based on features such as class, gender, age, and family relationships.

## Project Overview
The Titanic dataset is a classic machine learning dataset that provides structured data on passengers. Using this data, I developed an ensemble learning model to predict survival with high accuracy.

## Approach
1. **Data Preprocessing**:
   - Handled missing values for `Age`, `Fare`, and `Embarked`.
   - Scaled numerical features using `StandardScaler`.
   - Encoded categorical variables with `pd.get_dummies`.

2. **Modeling**:
   - Used an ensemble model with `VotingClassifier` combining:
     - Logistic Regression
     - Random Forest
     - Support Vector Classifier (SVC)

3. **Evaluation**:
   - Applied cross-validation for robust performance evaluation.
   - Achieved an average cross-validation accuracy of **82%**.

4. **Final Submission**:
   - Generated predictions and saved them as `submission.csv`.

## Results
- Cross-validation accuracy: 82%
- Kaggle leaderboard score: 0.76555

## Files
-  `titanic_survival_prediction.ipynb`: The main code file.
- `submission.csv`: Final predictions submitted to Kaggle.
- `README.md`: Project description.

