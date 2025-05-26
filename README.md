# diabetes-prediction-model
Machine learning model to predict diabetes using medical data
Diabetes Prediction Using Machine Learning
This project involves using a dataset of medical and lifestyle features to predict the likelihood of diabetes using machine learning models.

Steps Taken
Data Exploration – Inspected structure, missing values, and class distribution.

Data Cleaning – Removed duplicates, filtered out irrelevant classes, handled outliers.

Feature Engineering – Encoded categorical variables using LabelEncoder.

Preprocessing – Scaled features using RobustScaler and split data into training/test sets.

Modeling – Trained 3 models: Logistic Regression, Random Forest, and SVM.

Evaluation – Evaluated models using classification report, confusion matrix, and ROC AUC.

Model Tuning – Performed hyperparameter tuning using GridSearchCV for SVM.

Conclusion – SVM performed best with high recall and ROC AUC, making it suitable for minimizing false negatives in medical diagnosis.

 Challenges Faced
Class imbalance in the target variable affected initial accuracy.

Needed to understand and apply metrics beyond accuracy, like recall and ROC AUC.

Adjusting model parameters and selecting appropriate scalers required experimentation.

Visualizing multiple ROC curves and interpreting model performance in a business context.

How to Run
Clone this repo

Open the notebook in Jupyter or Colab

Run cells sequentially

