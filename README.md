# Student-academic-performance
Student Performance Prediction Model 🎓📊

Overview

This project aims to predict students' academic performance (e.g., final grades) based on various features such as study habits, socio-economic factors, and more. The dataset contains diverse features such as age, attendance, internet access, and previous academic records.

Dataset

Number of Columns: 23

Target Variable: TARGET_PREDICTION_PERCENT

Feature Examples:

age: Age of the student.

study_hrs_per_day: Average study hours per day.

family_financial_status: Family's financial condition.

prev_percent_1, prev_percent_2, prev_percent_3: Previous academic percentages.

Project Objectives

Build a machine learning model to predict the target variable.

Experiment with different algorithms to identify the best-performing model.

Optimize the model using hyperparameter tuning.

Evaluate the model using appropriate metrics.

Models Used

Gradient Boosting Regressor

Workflow

1. Data Preprocessing

Removed irrelevant columns.

No categorical columns were found for one-hot encoding; all features were numeric.

Split the dataset into training and testing sets (80:20 ratio).



2. Evaluation Metrics

Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.

R2 Score: Indicates the proportion of variance explained by the model.

4. Feature Importance

Extracted and displayed feature importances from the models to understand the contribution of each feature.

Code Highlights

Preprocessing: Scaled the data using StandardScaler to normalize features.

Results

Best-performing model and parameters are printed during runtime.

Evaluation metrics (MSE and R2) are displayed for each model.

Future Improvements

Add more advanced models such as neural networks.

Perform feature engineering for better predictions.

Use larger datasets to improve model generalization.

Dependencies

Python 3.7+

Pandas

NumPy

Scikit-learn
