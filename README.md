# Employee Attrition Prediction Using Machine Learning

## Overview
This project analyzes employee attrition using the IBM HR Analytics dataset and builds predictive machine learning models to identify employees at elevated risk of leaving the company.

The project was completed as part of the M.S. in Business Analytics program at the University of Cincinnati.

## Objective
Build a predictive classification model that identifies which employees are most likely to leave the company using demographic, job-related, and performance-related variables.

## Dataset
IBM HR Analytics Employee Attrition & Performance dataset

- Sample size: 1,480 employees
- Target variable: Attrition
- Problem type: Binary classification

## Methods
The project compares multiple supervised machine learning models, including:

- Logistic Regression
- Random Forest
- XGBoost
- Random Forest + SMOTE

Model evaluation emphasizes recall, precision, F1-score, and ROC-AUC.

## Results
The recommended model was Logistic Regression because it achieved strong recall and competitive ROC-AUC while remaining interpretable.

Key findings included:
- Overtime was strongly associated with attrition
- Lower job satisfaction was associated with attrition
- Lower monthly income was associated with attrition
- Younger employees were more likely to leave

## Files
```text
employee-attrition-ml/
├── employee_attrition_model.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── capstone_abstract.docx
├── README.md
└── requirements.txt
```

## Capstone Presentation
Watch the full project walkthrough:

https://youtu.be/NRoAxx89qDg

## Running the Project
Install dependencies:

```bash
pip install -r requirements.txt
```

Run the script:

```bash
python attrition_model.py
```

## Notes
This repository contains the final project code and supporting materials. The notebook/PDF/presentation version may include additional visuals and discussion not shown in the script alone.

## Author
Ben Harris  
M.S. Business Analytics – University of Cincinnati  

Data Science | Machine Learning | Healthcare & Business Analytics
