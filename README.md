Overview:
This project aims to develop a predictive model for Alberta's electricity market using machine learning techniques. The code files facilitate data preparation, model training, and parameter tuning.

Files:
FNCE 449 Project V1.py:
This file contains the initial version of the predictive model, which uses a set of selected features and optimized hyperparameters. It includes data preprocessing steps, feature engineering, model training, and evaluation using cross-validation. Visualizations in this version include time series plots of actual vs. predicted values and feature importance graphs, which help analyze model performance and significant predictors.

FNCE 449 Project V2.py:
This file is an exact copy of Version 1, with the addition of an hour lag feature to improve predictive accuracy. The same visualizations are included—time series plots and feature importance graphs—allowing for a direct comparison to assess the impact of the added lag feature.

FNCE 449 Parameter Tuning.py:
This script is dedicated to hyperparameter tuning, exploring different parameter combinations to find the optimal settings for the model, enhancing predictive accuracy and robustness.

⚠️ Warning: The parameter tuning script takes a significant amount of time to run (over 20 minutes on a mid-to-high-end gaming laptop). Running this file is not necessary, as V1 and V2 provide all the information needed for model evaluation.

Usage:
Each file can be executed independently to perform its respective function in the model development process.
