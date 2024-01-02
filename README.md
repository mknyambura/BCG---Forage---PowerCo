# PowerCo Analysis

## Overview
This repository contains an analysis of pricing and consumption data for PowerCo, a company that generates gas and electricity for its customers. The analysis includes data exploration, descriptive statistics, and the application of machine learning techniques for predicting churn.

## Files and Directories
- <strong>Data:</strong>
    - <strong>`price_data.csv:`</strong> Contains pricing information for different customers.
    - <strong>`client_data.csv:`</strong> Contains customer information, including churn labels.
- <strong>Analysis:</strong>
    - <strong>`PowerCo_Analysis.ipynb:`</strong> Jupyter Notebook containing the detailed analysis.
    - <strong>`README.md:`</strong> This file.

## Analysis Steps
1. <strong>Data Exploration:</strong>
    - Checked data types, descriptive statistics, and distributions of columns.
    - Visualized distributions using seaborn.
2.<strong>Machine Learning:</strong>
    - Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
    - Trained a RandomForestClassifier on the balanced dataset.
    - Evaluated the model performance using accuracy, confusion matrix, and feature importances.
3. <strong>Feature Importances Visualization:</strong>
    - Created bar plots to visualize feature importances.
    - Added data labels for better interpretation.

## Dependencies
- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

## Usage
1. Clone the repository:
```git clone https://github.com/your-username/PowerCo-Analysis.git
```
2. Open and run the Jupyter Notebook <strong>`PowerCo_Analysis.ipynb`</strong> for a detailed walkthrough of the analysis.

Happy exploring and analyzing data! 🚀✨