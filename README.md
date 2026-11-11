Diabetes Risk Prediction – Machine Learning Project

 Project Overview
 
This project explores a diabetes risk prediction dataset and applies machine learning classification algorithms to predict a person's diabetes risk category: Low, Moderate, or High.
The project covers data inspection, exploratory data analysis (EDA), preprocessing, class-imbalance handling, model training, and performance comparison.
Disclaimer: This is an educational machine learning project, not a medical diagnostic tool. Predictions must not replace advice or diagnosis from a qualified healthcare professional.

 Dataset Information

Item	                Description
Dataset file	        diabetes_risk_prediction_dataset(1).csv
Number of records	    50,000
Number of columns	    41
Problem type	        Multiclass classification
Target column	        Diabetes_Risk
Target classes	        Low, Moderate, High


Target distribution

Diabetes risk	    Records	        Percentage
High	            36,593	        73.19%
Moderate	        12,937	        25.87%
Low	                470	            0.94%
Total	            50,000	        100%

The target is strongly imbalanced. The Low-risk class represents less than 1% of the records, so accuracy alone is not sufficient to evaluate a model.


 Dataset Features

The dataset contains demographic, physical, clinical, lifestyle, and recommendation-related information.

Demographic features
- Patient_ID
- Age
- Gender
- Country
- Work_Type
- Residence_Type

Physical and clinical measurements
- Height_cm
- Weight_kg
- BMI
- Waist_Circumference_cm
- Blood_Glucose
- HbA1c
- Fasting_Blood_Sugar
- Insulin_Level
- Blood_Pressure_Systolic
- Blood_Pressure_Diastolic
- Total_Cholesterol
- HDL
- LDL
- Triglycerides
- Heart_Rate

Lifestyle and health-history features
- Physical_Activity_Level
- Exercise_Hours_Per_Week
- Daily_Walking_Minutes
- Diet_Quality
- Sugar_Intake_Level
- Sleep_Hours
- Stress_Level
- Smoking_Status
- Alcohol_Consumption
- Family_History_Diabetes
- Hypertension
- Heart_Disease
- Fatty_Liver
- PCOS
- Medication_Adherence
- Daily_Water_Intake_L

Additional fields
- Diabetes_Risk_Score
- AI_Health_Recommendation
- Doctor_Consultation_Needed

Target variable
- Diabetes_Risk


Project Objectives
1. Understand the dataset using descriptive statistics and EDA.
2. Identify missing values, duplicates, and unusual values.
3. Explore relationships between health indicators and diabetes risk.
4. Prepare numerical and categorical data for machine learning.
5. Compare multiple classification algorithms.
6. Investigate the effect of class imbalance and SMOTE.
7. Select a model based on appropriate evaluation metrics.


Technologies and Libraries
- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)