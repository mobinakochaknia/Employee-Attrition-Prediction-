# Employee Attrition Prediction Using KNN, Random Forest, Bagging, and AdaBoost
## Project Overview
This project focuses on predicting employee attrition based on a dataset containing various employee characteristics. The goal is to explore key attributes influencing employee turnover and to develop machine learning models that classify employees as retained or attrited. Various classification techniques, including K-Nearest Neighbors (KNN), Random Forest, Bagging, and AdaBoost, are applied and compared for accuracy.

## Dataset
The dataset provides a range of attributes about employees, such as Age, BusinessTravel, Department, YearsAtCompany, and MonthlyIncome. The target variable is Attrition, indicating whether an employee has left the company

## Preprocessing
- Label Encoding: Applied to categorical columns.
- Feature Scaling: Implemented using StandardScaler to scale numerical features.

## Modeling Techniques
- K-Nearest Neighbors (KNN): A custom KNN classifier is implemented to evaluate model performance with varying k values.
- Random Forest: Leveraging GridSearchCV for hyperparameter tuning, Random Forest is trained and evaluated for feature importance.
- Bagging with KNN: A Bagging classifier is combined with KNN (best k from previous experiments) to assess its impact on model stability.
- AdaBoost: Tuning with GridSearchCV to optimize parameters like n_estimators and learning_rate.

## Model Evaluation
Each model's performance is compared using:
- Accuracy Score
- Classification Report (Precision, Recall, F1-Score)
- Confusion Matrix

Visualizations include:
- Confusion Matrix Heatmaps
- Feature Importance Plot for Random Forest and AdaBoost
- Model Accuracy Comparison Plot

## Results
The results indicate the effectiveness of each model, with the **best model** based on accuracy. Additionally, a feature importance plot highlights the most influential features for predicting attrition.
