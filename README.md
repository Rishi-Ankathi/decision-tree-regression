# Decision Tree Regression using RandomizedSearchCV

This project demonstrates Decision Tree Regression using the California Housing dataset with hyperparameter tuning through RandomizedSearchCV.

## Features

- Loads California Housing dataset
- Splits dataset into training and testing sets
- Performs hyperparameter tuning using RandomizedSearchCV
- Trains a DecisionTreeRegressor model
- Evaluates model performance using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Visualizes the trained Decision Tree
- Interactive Streamlit interface

## Technologies Used

- Python
- Streamlit
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- SciPy

## Hyperparameters Tuned

- criterion
- max_depth
- min_samples_split
- min_samples_leaf
- max_features

## Dataset

California Housing Dataset from Scikit-learn.

## Model Workflow

1. Load Dataset
2. Split Data
3. Define Decision Tree Regressor
4. Apply RandomizedSearchCV
5. Train Best Model
6. Make Predictions
7. Evaluate Performance
8. Visualize Decision Tree

## Performance Metrics

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
