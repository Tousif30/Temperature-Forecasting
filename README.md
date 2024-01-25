# Temperature-Forecasting
## Overview
This project involves the prediction of future temperature data via the utilization of XGBRegression model from the XGBoost library in Python. The data for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/mnassrib/jena-climate).
## Methodology
Firstly checks were conducted to see if there were any null or duplicated data. Various features were extracted from the dates of the dataset so that they can be used in the model training and lag features were created too. Initially the model was trained by cross-validation were the dataset was divided into five folds. Finally the model was trained using the full dataset and predictions were generated.
