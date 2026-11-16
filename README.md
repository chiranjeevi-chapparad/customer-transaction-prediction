# Customer Transaction Prediction

## Project Overview
A machine learning classification project that analyses anonymized customer-related data to predict whether an observation belongs to the positive transaction class.

The project focuses on exploratory data analysis, data preprocessing, model development and evaluation.

## Dataset Overview
- Total records: 200,000
- Predictor variables: 200
- Target variable: `target`
- Identifier: `ID_code`
- Missing values: 0
- Duplicate records: 0

The predictor variables are anonymized numerical features.

## Exploratory Data Analysis
Initial analysis identified:
- Class imbalance: 89.951% class 0 and 10.049% class 1.
- All 200 predictor variables are numerical.
- No constant features were found.
- Potential outliers were identified using the IQR method.
- No feature pairs had an absolute correlation above 0.80.
- Individual feature correlations with the target were relatively weak.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data validation
2. Exploratory Data Analysis
3. Data preprocessing
4. Model development
5. Model optimisation
6. Model evaluation

## Project Status
Currently in progress – Exploratory Data Analysis completed.

## Author
Chiranjeevi R Chapparad
[GitHub](https://github.com/chiranjeevi-chapparad)
