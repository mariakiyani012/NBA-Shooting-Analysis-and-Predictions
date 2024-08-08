# NBA Players Shooting Analysis and Predictions

This repository contains Python code for analyzing shooting data of NBA players, focusing on various aspects such as shot accuracy, shot locations, player performance, and model predictions.

## Contents

1. **Data Exploration and Preprocessing**:
   - Loading the dataset (`nba_players_shooting.csv`)
   - Understanding variables and handling missing values

2. **Feature Engineering**:
   - Calculating new variables (`RANGE_num`, `RANGE_region`)
   - Sorting categorical data (`RANGE`)

3. **Exploratory Data Analysis (EDA)**:
   - Visualizing field goal percentages by players
   - Plotting shot locations by player
   - Segmenting the field into regions and visualizing shot distribution

4. **Model Building and Evaluation**:
   - Preparing data for machine learning models
   - Training various classifiers (Logistic Regression, Random Forest, SVC, MLP)
   - Evaluating model performance using accuracy and ROC curves

5. **Hyperparameter Tuning**:
   - Using GridSearchCV to optimize model parameters
   - Fine-tuning SVC with linear kernel and logistic regression calibration

6. **Result Interpretation**:
   - Comparing original vs calibrated model performance
   - Plotting reliability curves for model evaluation

## Usage
- Ensure Python and necessary libraries are installed (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`).
- Execute the notebooks or scripts sequentially to replicate the analysis.
- Modify hyperparameters or add additional models as needed for further experimentation.

## Requirements
- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
