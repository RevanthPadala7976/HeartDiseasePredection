# HeartDiseasePredection
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

**Decision Tree Classifier:** Achieved 98.54% accuracy.
**Random Forest Classifier:** Achieved 98.54% accuracy.
**Naive Bayes:** Achieved 80% accuracy.
**Support Vector Machine (SVM):** Achieved 98.54% accuracy.
**Neural Network:** Achieved 72.68% accuracy.
### Cross-Validation
Performed cross-validation to ensure the robustness of the models. The cross_val_score function was used to compute the accuracy, precision, recall, and F1 score across multiple folds.

### Model Comparison
The performance of all models was compared using evaluation metrics and visualizations to determine their effectiveness in predicting heart disease.

## Conclusion

Most models, including Decision Tree, Random Forest, and SVM, achieved high accuracy of 98.54%, demonstrating their effectiveness in heart disease prediction. The Neural Network model, while performing reasonably well, achieved a lower accuracy of 72.68%. These results suggest that machine learning models can significantly aid in the prediction of heart disease, providing valuable support to healthcare professionals.
