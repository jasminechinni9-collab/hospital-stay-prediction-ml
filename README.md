# Hospital Stay Prediction using Machine Learning

## Project Overview
This project uses Machine Learning algorithms to predict a patient's length of stay in a hospital based on patient and hospital-related information.

The target variable `Stay` contains 11 different classes, making this a multiclass classification problem.

## Dataset
The dataset contains hospital and patient-related information, including:
- Hospital type and city
- Department
- Ward type
- Bed grade
- Type of admission
- Severity of illness
- Age of patient
- Visitors
- Admission deposit

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Project Workflow
1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Missing Value Handling
5. Data Visualization
6. Feature Encoding
7. Model Building
8. Class Imbalance Analysis
9. Model Evaluation
10. Model Comparison

## Machine Learning Models
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- XGBoost Classifier

## Model Evaluation
Models were evaluated using:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Best Performing Model
XGBoost Classifier achieved the highest accuracy among the evaluated models.

Best recorded accuracy: **42.02%**

## Challenges Faced
- Multiclass classification with 11 target classes.
- Imbalanced target categories.
- Missing values in some features.
- Categorical feature encoding.
- Model overfitting.
- Computational limitations while training models.

## Conclusion
This project demonstrates a complete Machine Learning workflow for hospital stay prediction, including data preprocessing, exploratory data analysis, handling class imbalance, model training, and performance evaluation.
