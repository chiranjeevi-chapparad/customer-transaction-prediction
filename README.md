# Customer Transaction Prediction

## Project Overview
A machine learning classification project that predicts customer transaction outcomes using anonymized numerical features.

## Dataset
- 200,000 records
- 200 numerical predictor variables
- Binary target variable
- Approximately 90:10 class distribution

The dataset contains anonymized features (`var_0` to `var_199`).

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data loading and validation
2. Exploratory Data Analysis
3. Data preprocessing
4. Handling class imbalance
5. Logistic Regression
6. Decision Tree
7. Random Forest
8. Classification threshold tuning
9. Model evaluation and comparison

## Model Performance

| Metric | Logistic Regression | Decision Tree | Random Forest |
|---|---:|---:|---:|
| Accuracy | 87.83% | 83.70% | 84.89% |
| Precision | 42.23% | 22.09% | 34.23% |
| Recall | 57.44% | 24.60% | 54.60% |
| F1 Score | 48.67% | 23.28% | 42.08% |
| ROC-AUC | 85.99% | 63.90% | 82.06% |

Logistic Regression achieved the best overall performance among the evaluated configurations.

## Key Learning Outcomes
- Exploratory data analysis
- Class imbalance handling
- Feature scaling
- Classification model development
- Model evaluation
- Threshold optimization
- Data visualization

## Repository Structure
```text
customer-transaction-prediction/
├── README.md
├── .gitignore
└── notebooks/
    └── customer_transaction_prediction.ipynb
```

## How to Run
1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook using Jupyter Notebook.
4. Run the notebook cells sequentially.

## Author
**Chiranjeevi R Chapparad**

GitHub: https://github.com/chiranjeevi-chapparad
