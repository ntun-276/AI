# Artificial Intelligence Project 🔬💡
Heart Disease Prediction (Dự đoán bệnh tim) ❤️‍🩹

## 🔍 Description:
In this project, they delve into a dataset encapsulating various health metrics from heart patients, including age, blood pressure, heart rate, and more. The goal is to develop a predictive model capable of accurately identifying individuals with heart disease. Given the grave implications of missing a positive diagnosis, our primary emphasis is on ensuring that the model identifies all potential patients, making recall for the positive class a crucial metric.

## 📝 Key Features:
- `age` : Age of the patient in years.
- `sex` : Gender of the patient (0 = male, 1 = female).
- `cp` : Chest pain type (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic).
- `trestbps` : Resting blood pressure in mm Hg.
- `chol` : Serum cholesterol in mg/dl.
- `fbs` : Fasting blood sugar level, categorized as above 120 mg/dl (1 = true, 0 = false).
- `restecg` : Resting electrocardiographic results (0: Normal, 1: Having ST-T wave abnormality, 2: Showing probable or definite left ventricular hypertrophy).
- `thalach` : Maximum heart rate achieved during a stress test.
- `exang` : Exercise-induced angina (1 = yes, 0 = no).
- `oldpeak` : ST depression induced by exercise relative to rest.
- `slope` : Slope of the peak exercise ST segment (0: Upsloping, 1: Flat, 2: Downsloping).
- `ca` : Number of major vessels (0-4) colored by fluoroscopy.
- `thal` : Thalium stress test result (0: Normal, 1: Fixed defect, 2: Reversible defect, 3: Not described).
- `target` : Heart disease status (0 = no disease, 1 = presence of disease).

Data Source: https://www.kaggle.com/code/farzadnekouei/heart-disease-prediction

## 🎯 Accuracy Results of Machine Learning Models:
|  Model                   |  Accuracy  |
|--------------------------|------------|
|  Decision Tree           |    0.79    |
|  Random Forest           |    0.84    |
|  K-Nearest Neighbors     |    0.79    |
|  Support Vector Machine  |    0.84    |
