# Heart-Disease-Prediction

## 🚀 Project Overview

Heart disease is one of the leading causes of death worldwide. Early detection can significantly reduce risks and improve patient outcomes.
This project uses machine learning to analyze patient health data and provide a heart disease risk prediction.

The application is deployed as an interactive web app allowing users to input medical details and instantly receive predictions.

## 🧠 Machine Learning Approach

• Supervised learning classification model

• Trained on a heart disease dataset (UCI / Cleveland-style)

• Predicts:

🟢 Low Risk of Heart Disease

🔴 High Risk of Heart Disease

## 📊 Input Features Used

The model uses the following clinical features:

| Feature                               | Description                             |
| ------------------------------------- | --------------------------------------- |
| **Age**                               | Age of the patient (years)              |
| **Gender**                            | Male / Female                           |
| **Chest Pain Type (cp)**              | Type of chest pain experienced          |
| **Resting Blood Pressure (trestbps)** | Blood pressure at rest (mmHg)           |
| **Cholesterol (chol)**                | Serum cholesterol level (mg/dL)         |
| **Fasting Blood Sugar (fbs)**         | Whether fasting blood sugar > 120 mg/dL |
| **Resting ECG (restecg)**             | Resting electrocardiographic results    |
| **Max Heart Rate (thalach)**          | Maximum heart rate achieved             |
| **Exercise Induced Angina (exang)**   | Chest pain during exercise              |
| **Oldpeak**                           | ST depression induced by exercise       |
| **ST Slope (slope)**                  | Slope of peak exercise ST segment       |

## 🔍 Risk Classification Logic

### 🟢 Low Risk of Heart Disease

• Normal blood pressure and cholesterol levels

• No exercise-induced angina

• Normal ECG results

• Higher maximum heart rate

• Minimal ST depression (Oldpeak ≤ 1.0)

• Upsloping ST segment

➡️ Indicates healthy cardiovascular function

### 🔴 High Risk of Heart Disease

• High blood pressure and cholesterol

• Exercise-induced angina present

• Abnormal ECG findings

• Lower maximum heart rate

• Significant ST depression (Oldpeak > 2.0)

• Flat or downsloping ST segment

➡️ Indicates higher probability of heart disease

## ✅ Conclusion

The Heart Disease Prediction System demonstrates how machine learning can be effectively applied to healthcare data to support early risk assessment of heart disease. By analyzing key clinical indicators such as blood pressure, cholesterol levels, ECG results, exercise-induced angina, and ST-segment changes, the model provides a clear classification of Low Risk and High Risk cases.
