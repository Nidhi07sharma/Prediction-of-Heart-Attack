# Prediction-of-Heart-Attack

Project Description

Heart disease is one of the leading causes of death worldwide. Early prediction of heart attack risk can significantly improve patient outcomes by enabling timely medical intervention and lifestyle changes. This project leverages machine learning to predict the likelihood of heart disease in patients based on medical and demographic data. The models developed aim to provide accurate predictions that can assist healthcare professionals in assessing patient risk and making informed decisions.

Objective

The primary objective of this project is to develop a machine-learning model that predicts the risk of heart disease using patient data. The key goals are:

To analyze the importance of various medical and demographic factors in predicting heart disease risk.
To train and evaluate different machine learning models (Logistic Regression, Random Forest, Decision Tree) on the dataset.
To identify the best model that can provide accurate predictions of heart disease risk.
Dataset
The dataset used in this project contains 302 rows and 14 columns, including patients' medical and demographic features. These features are:

age: Age of the patient (in years)
sex: Sex of the patient (1 = male, 0 = female)
cp: Chest pain type (0-3)
trestbps: Resting blood pressure (in mm Hg)
chol: Serum cholesterol (in mg/dl)
fbs: Fasting blood sugar (>120 mg/dl or not, 1 = yes, 0 = no)
restecg: Resting electrocardiographic results
thalach: Maximum heart rate achieved
exang: Exercise-induced angina (1 = yes, 0 = no)
oldpeak: ST depression induced by exercise relative to rest
slope: Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping)
ca: Number of major vessels colored by fluoroscopy
thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
target: Heart attack risk (1 = risk, 0 = no risk)

Models and Results

The following machine learning models were trained and evaluated:

1. Logistic Regression (RFE)
Accuracy: 85.25%
Kappa Value: 0.70
Precision, Recall, F1-Score: Balanced performance with high recall for heart attack risk (1).

3. Random Forest
Accuracy: 80.33%
The model provides valuable insights into feature importance.

5. Decision Tree
Accuracy: 72.13%
A simple model with moderate performance.

Conclusion
Best Model: Logistic Regression with Recursive Feature Elimination (RFE) performed the best in terms of accuracy and Kappa value. It showed strong performance in distinguishing between patients at risk and not at risk for heart disease.

Feature Importance:
Key features such as chest pain type (cp), maximum heart rate achieved (thalach), and thalassemia (thal) were crucial in predicting the likelihood of heart disease.

.
Technologies Used

Python: Used for data preprocessing, feature engineering, and model development.
Scikit-learn: For machine learning algorithms and model evaluation.
Matplotlib/Seaborn: For data visualization and feature importance analysis.
