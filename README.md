# EV-Range-Estimator-using-GenAI-and-ML-model
A simple machine learning project to predict the driving range of electric vehicles based on technical features like battery capacity and efficiency. Includes dataset cleaning, feature selection, regression modeling, and result visualization.

## Problem Statement
Predict how far an electric vehicle can travel on a full charge (driving range) using its technical specifications. Accurate range prediction helps buyers and manufacturers make informed decisions.

## Solution Approach
**Data Cleaning:** Removed unnecessary columns and filled in missing values.
**Feature Selection:** Used battery capacity, efficiency, and top speed.
**Model:** Linear Regression to estimate EV range.
**Evaluation:** Assessed accuracy with Mean Absolute Error (MAE).

## Files Included
`ev_range_prediction.ipynb` – Jupyter notebook: analysis, clean-up, modeling and visualization.
`electric_vehicles_spec_2025_clean.csv` – Final cleaned dataset used for modeling.

## How to Run
1. Clone/download the repository.
2. Open Jupyter Notebook (Anaconda/Colab).
3. Run `ev_range_prediction.ipynb` after placing the CSV files in your working directory.
4. View predictions and plots in the notebook output.

## Requirements
- Python 3.x
- Google collab
- pandas, numpy, matplotlib, scikit-learn

## Results
The model predicts EV range with reasonable accuracy. Actual vs. predicted range is visualized in the results section.

## Credits
- Dataset: [Kaggle Electric Vehicle Specs Database](https://ev-database.org)
- Project by Sanjana Bhosale
