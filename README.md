# HeartDiseasePredection
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white" alt="Anaconda">
  <img src="https://img.shields.io/badge/Matplotlib-3C5280?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
</p>

## Introduction

This project aims to predict heart disease, a critical health concern affecting millions of people globally. Accurate prediction of heart disease can significantly impact healthcare by enabling early intervention and personalized treatment plans. By leveraging machine learning algorithms, this project seeks to enhance the accuracy of heart disease prediction, aiding medical professionals in their decision-making processes.

In this analysis, we utilize a dataset containing various health-related features, such as age, cholesterol levels, and blood pressure, to build predictive models for heart disease. The goal is to provide insights and predictions that can assist healthcare providers in identifying high-risk patients and implementing preventive measures.

## Dataset

The dataset used for this project includes information on patients' health metrics and demographics. Some of the important features include:

Age
Sex
Chest Pain Type (cp)
Resting Blood Pressure (trestbps)
Serum Cholesterol (chol)
Fasting Blood Sugar (fbs)
Resting Electrocardiographic Results (restecg)
Maximum Heart Rate Achieved (thalach)
Exercise Induced Angina (exang)
ST Depression Induced by Exercise Relative to Rest (oldpeak)
Slope of the Peak Exercise ST Segment (slope)
Number of Major Vessels Colored by Fluoroscopy (ca)
Thalassemia (thal)
Target (presence of heart disease)

## Data Preprocessing

To prepare the data for analysis, we performed the following steps:

Handled Missing Values: Checked for and imputed missing values where necessary.
Label Encoding: Converted categorical features into numerical representations using label encoding.
Feature Scaling: Applied scaling to ensure all features contribute equally to the model.

## Exploratory Data Analysis (EDA)

Conducted exploratory data analysis to gain insights into the dataset. Here are some key findings:

Older individuals tend to have a higher prevalence of heart disease.
Certain chest pain types are strongly associated with heart disease.
Higher levels of serum cholesterol and resting blood pressure are risk factors for heart disease.
The presence of exercise-induced angina is a significant indicator of heart disease.

## Model Building and Evaluation

Built several machine learning models to predict heart disease, including Decision Tree, Random Forest, Support Vector Machine (SVM), and Neural Network. The performance of these models was evaluated using accuracy scores, classification reports, and confusion matrices.

- **Decision Tree Classifier:** Achieved 98.54% accuracy.
- **Random Forest Classifier:** Achieved 98.54% accuracy.
- **Naive Bayes:** Achieved 80% accuracy.
- **Support Vector Machine (SVM):** Achieved 98.54% accuracy.
- **Neural Network:** Achieved 72.68% accuracy.
  
### Cross-Validation
Performed cross-validation to ensure the robustness of the models. The cross_val_score function was used to compute the accuracy, precision, recall, and F1 score across multiple folds.

### Model Comparison
The performance of all models was compared using evaluation metrics and visualizations to determine their effectiveness in predicting heart disease.

## Conclusion

Most models, including Decision Tree, Random Forest, and SVM, achieved high accuracy of 98.54%, demonstrating their effectiveness in heart disease prediction. The Neural Network model, while performing reasonably well, achieved a lower accuracy of 72.68%. These results suggest that machine learning models can significantly aid in the prediction of heart disease, providing valuable support to healthcare professionals.
