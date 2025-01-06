# Predictive Analysis: Loan Prediction Project

## Project Overview
This project utilizes machine learning models to predict loan approval based on various customer attributes. The primary goal is to create a predictive model and evaluate its performance using metrics like accuracy.

## Files Included

### Python Notebook and Code
- **`Predictive_Analysis_Loan_Prediction.pdf`**: This document contains the Python notebook detailing the analysis, visualizations, and model training.

### Dataset Files
- **`train.csv`**: Training dataset with labeled examples for model training.
- **`test.csv`**: Testing dataset used for evaluating the predictive models.

## Features of the Project
1. **Exploratory Data Analysis (EDA):**
   - Univariate and bivariate analysis of key features like Gender, Credit History, and Property Area.
   - Visualization of distributions and correlations.
2. **Data Preprocessing:**
   - Handling missing values through imputation.
   - Feature engineering (e.g., Total Income, EMI, and Balance Income).
3. **Model Building and Evaluation:**
   - Logistic Regression.
   - Decision Trees.
   - Random Forest with Grid Search.
   - XGBoost Classifier.
4. **Performance Metrics:**
   - Accuracy scores for each model.
   - Feature importance visualization.

## Prerequisites
- Python 3.8 or above.
- Required Python libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - xgboost

## Instructions to Run
1. Ensure all files (datasets and notebook) are in the same directory.
2. Install the required Python libraries using pip:
   ```
   pip install pandas numpy seaborn matplotlib scikit-learn xgboost
   ```
3. Load the datasets (`train.csv` and `test.csv`).
4. Follow the analysis and model training steps as outlined in the notebook.

## Results and Insights
- Logistic Regression achieved the highest accuracy (78.92%) among all models.
- Credit History was identified as the most critical feature influencing loan approval.
- Random Forest with Grid Search provided a robust model with accuracy close to Logistic Regression.

## Future Enhancements
- Incorporate additional datasets for better generalization.
- Apply advanced hyperparameter optimization techniques.
- Experiment with ensemble models for improved accuracy.
