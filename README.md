# Multi-Disease Prediction System Using Continuous Health Data 

## Overview
This project aims to develop a robust machine learning system capable of detecting multiple diseases using continuous data from various datasets. The system is designed to facilitate user interaction through a web-based front end built with Streamlit, allowing users to input their health data and receive disease predictions.

## Datasets
The project utilizes three datasets:

1. **Diabetes Dataset (diabetes.csv)**
   - Features: 
     - `Pregnancies`
     - `Glucose`
     - `BloodPressure`
     - `SkinThickness`
     - `Insulin`
     - `BMI`
     - `DiabetesPedigreeFunction`
     - `Age`
     - `Outcome` (Target variable)
   - Sample Data:
     ```
     6,148,72,35,0,33.6,0.627,50,1
     1,85,66,29,0,26.6,0.351,31,0
     ```

![image](https://github.com/user-attachments/assets/36f88f2b-0e1e-4c79-a9cf-0b2635f0afd5)
     

2. **Heart Disease Dataset (heart.csv)**
   - Features:
     - `age`
     - `sex`
     - `cp` (chest pain type)
     - `trestbps` (resting blood pressure)
     - `chol` (cholesterol)
     - `fbs` (fasting blood sugar)
     - `restecg`
     - `thalach` (maximum heart rate)
     - `exang` (exercise induced angina)
     - `oldpeak`
     - `slope`
     - `ca` (number of major vessels)
     - `thal`
     - `target` (Diagnosis)
   - Sample Data:
     ```
     63,1,3,145,233,1,0,150,0,2.3,0,0,1
     37,1,2,130,250,0,1,187,0,3.5,0,0,2
     ```

![image](https://github.com/user-attachments/assets/7ce7d3e2-46ba-493b-90c9-0ccc8873a98b)


3. **Parkinson’s Disease Dataset (parkinsons.csv)**
   - Features:
     - `name`
     - `MDVP:Fo(Hz)`
     - `MDVP:Fhi(Hz)`
     - `MDVP:Flo(Hz)`
     - `MDVP:Jitter(%)`
     - `MDVP:Jitter(Abs)`
     - `MDVP:RAP`
     - `MDVP:PPQ`
     - `Jitter:DDP`
     - `MDVP:Shimmer`
     - `MDVP:Shimmer(dB)`
     - `Shimmer:APQ3`
     - `Shimmer:APQ5`
     - `MDVP:APQ`
     - `Shimmer:DDA`
     - `NHR`
     - `HNR`
     - `status`
     - `RPDE`
     - `DFA`
     - `spread1`
     - `spread2`
     - `D2`
     - `PPE`
   - Sample Data:
     ```
     phon_R01_S01_1,119.99200,157.30200,74.99700,0.00784,0.00007,0.00370,0.00554,0.01109,0.04374,0.42600,0.02182,0.03130,0.02971,0.06545,0.02211,21.03300,1,0.414783,0.815285,-4.813031,0.266482,2.301442,0.284654
     ```

## Steps Followed

1. **Data Gathering**
   - Collected the three datasets mentioned above, each focusing on different health conditions.

2. **Data Preprocessing**
   - Cleaned and prepared the datasets for analysis, including handling missing values and encoding categorical variables where necessary.

3. **Model Training**
   - Implemented machine learning models to train on the preprocessed datasets. The models were selected based on their suitability for classification tasks.

4. **Evaluation**
   - Assessed the performance of the models using relevant metrics (e.g., accuracy, precision, recall, F1 score) to ensure they meet the required standards for disease prediction.

5. **Front-End Development**
   - Developed a Streamlit application that allows users to enter their data for all three diseases. The application provides a seamless experience for users to receive predictions based on their input.


![image](https://github.com/user-attachments/assets/43a92592-e5c2-45a7-a341-4e973c2df51f)
