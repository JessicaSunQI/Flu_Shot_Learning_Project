# Flu Shot Learning Project

This repository contains work related to the "Flu Shot Learning: Predict H1N1 and Seasonal Flu Vaccines" competition hosted by DrivenData. The objective is to predict the likelihood of individuals receiving H1N1 and seasonal flu vaccines based on survey data.

## Project Overview

The project involves analyzing survey responses from the National 2009 H1N1 Flu Survey, which includes information about respondents' backgrounds, opinions, and health behaviors. The goal is to build predictive models that estimate the probabilities of individuals getting vaccinated against H1N1 and seasonal flu.

## Data

The dataset comprises:

- **training_set_features.csv**: Features from the training data.
- **training_set_labels.csv**: Labels indicating vaccination status for the training data.
- **test_set_features.csv**: Features from the test data for which predictions are to be made.

## Repository Structure

- **Neural_Network_Model.ipynb**: Jupyter notebook implementing a neural network model for prediction.
- **Random_Forest_Model.ipynb**: Jupyter notebook implementing a random forest model for prediction.
- **Random_forest_Test_Data.ipynb**: Jupyter notebook applying the random forest model to test data.
- **Tree Models/**: Directory containing implementations of various tree-based models.
- **NN Model predictions.csv**: Predictions from the neural network model.
- **final Separate XGBoost Models submission.csv**: Submission file with predictions from separate XGBoost models.
- **numerical_col_imputation_analysis.csv**: Analysis related to imputation of numerical columns.
- **treemodel_test_data.csv**: Test data processed for tree models.

## Models Implemented

- **Neural Network**: Implemented using the `Neural_Network_Model.ipynb` notebook.
- **Random Forest**: Implemented using the `Random_Forest_Model.ipynb` notebook.
- **XGBoost**: Predictions from separate XGBoost models are compiled in `final Separate XGBoost Models submission.csv`.

## Getting Started

To explore or reproduce the analyses:

1. Clone the repository:
   ```bash
   git clone https://github.com/JessicaSunQI/Flu_Shot_Learning_Project.git
