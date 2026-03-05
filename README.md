

#Healthcare Data Analysis: Diabetes Risk Assessment


This project analyzes a healthcare dataset to identify key factors associated with diabetes risk. The objective is to perform data cleaning, exploratory data analysis (EDA), and statistical comparison to uncover meaningful patterns in patient health data.

The analysis focuses on identifying health indicators such as glucose level, BMI, and age that may influence diabetes occurrence.

Dataset

Dataset Source:
Kaggle

Dataset: Pima Indians Diabetes Dataset

Dataset Description

The dataset contains medical information for 768 patients and includes several health-related attributes used to predict diabetes risk.

Target Variable:

Outcome

0 → Non-Diabetic

1 → Diabetic

Features
Feature	Description
Pregnancies	Number of pregnancies
Glucose	Blood glucose concentration
BloodPressure	Blood pressure measurement
SkinThickness	Skin fold thickness
Insulin	Serum insulin level
BMI	Body Mass Index
DiabetesPedigreeFunction	Genetic influence factor
Age	Age of patient
Outcome	Diabetes diagnosis
Project Objectives

Perform data cleaning and preprocessing

Conduct exploratory data analysis

Identify key health indicators related to diabetes

Extract meaningful insights from patient data

Present findings through visualizations and statistical analysis

Data Cleaning

The dataset contained invalid zero values in several medical attributes where zero is not medically possible.

The following preprocessing steps were applied:

Replaced zero values in Glucose, BMI, BloodPressure, Insulin, and SkinThickness using median imputation

Checked and removed duplicate records

Verified data distributions using summary statistics

Median was used because medical datasets often contain skewed distributions.

Exploratory Data Analysis

Several visualizations were created to analyze relationships between patient attributes and diabetes outcomes.

Key analyses included:

Distribution of Age, BMI, and Glucose

Comparison of health indicators between diabetic and non-diabetic patients

Correlation analysis between variables

Risk segmentation by age group

Key Insights

Diabetic patients show approximately 28–29% higher average glucose levels compared to non-diabetic patients.

Diabetes prevalence increases among individuals above the age of 40.

BMI shows a moderate association with diabetes risk.

The dataset contains a moderate class imbalance, with around 35% diabetic cases.

These findings suggest that glucose level, BMI, and age are important indicators for diabetes risk assessment.

Tools and Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Project Structure
Healthcare-Data-Analysis/
│
├── data/
│   └── diabetes.csv
│
├── analysis.ipynb
├── report.pdf
├── requirements.txt
└── README.md
Conclusion

The analysis highlights glucose level as the strongest indicator associated with diabetes risk, followed by BMI and age. These insights emphasize the importance of early health monitoring and preventive care strategies to reduce diabetes prevalence.
