# Heart-Disease-Prediction
A machine learning project for predicting heart disease risk, including data preprocessing, model training, evaluation, and deployment


# Heart Disease Prediction

© 2024

---

## Project Overview
This project focuses on predicting the risk of heart disease based on a dataset collected by eHealth Africa. The data includes various medical and demographic factors that can influence heart disease, collected from patients in the southern and northern parts of Nigeria.

This project will involve applying machine learning and data science techniques to build predictive models that can help analyze heart disease risk factors and improve health outcomes. The primary goal is to provide insights for healthcare professionals to make data-driven decisions in preventive and predictive healthcare.

## Data Dictionary

### Table 1: Heart Disease Data Description

| Variable Name | Description                               | Role   | Type        | Units      |
|---------------|-------------------------------------------|--------|-------------|------------|
| `age`         | Age of the patient                        | Feature| Integer     | years      |
| `sex`         | Gender of the patient                     | Feature| Categorical | -          |
| `cp`          | Chest pain type                           | Feature| Categorical | -          |
| `trestbps`    | Resting blood pressure (on admission)     | Feature| Integer     | mm/Hg      |
| `chol`        | Serum cholesterol                         | Feature| Integer     | mg/dl      |
| `fbs`         | Fasting blood sugar > 120 mg/dl           | Feature| Categorical | -          |
| `restecg`     | Resting electrocardiographic results      | Feature| Categorical | -          |
| `thalach`     | Maximum heart rate achieved               | Feature| Integer     | -          |
| `exang`       | Exercise induced angina                   | Feature| Categorical | -          |
| `oldpeak`     | ST depression induced by exercise relative to rest | Feature | Float | -      |
| `slope`       | Slope of the peak exercise ST segment     | Feature| Categorical | -          |
| `ca`          | Number of major vessels (0-3) colored by fluoroscopy | Feature | Integer | - |
| `thal`        | Thallium stress test result               | Feature| Categorical | -          |
| `status`      | Diagnosis of heart disease                | Target | Categorical | -          |

This dataset will be used to analyze and predict heart disease presence in patients. The models developed in this project aim to support risk analysis and predictive insights in the healthcare sector.

## Project Goals
- Develop machine learning models to predict heart disease risk.
- Analyze feature importance and risk factors associated with heart disease.
- Use data-driven insights to assist healthcare professionals in patient assessment.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone # Heart Disease Prediction

© 2024

---

## Project Overview
This project focuses on predicting the risk of heart disease based on a dataset collected by eHealth Africa. The data includes various medical and demographic factors that can influence heart disease, collected from patients in the southern and northern parts of Nigeria.

This project will involve applying machine learning and data science techniques to build predictive models that can help analyze heart disease risk factors and improve health outcomes. The primary goal is to provide insights for healthcare professionals to make data-driven decisions in preventive and predictive healthcare.

## Data Dictionary

### Table 1: Heart Disease Data Description

| Variable Name | Description                               | Role   | Type        | Units      |
|---------------|-------------------------------------------|--------|-------------|------------|
| `age`         | Age of the patient                        | Feature| Integer     | years      |
| `sex`         | Gender of the patient                     | Feature| Categorical | -          |
| `cp`          | Chest pain type                           | Feature| Categorical | -          |
| `trestbps`    | Resting blood pressure (on admission)     | Feature| Integer     | mm/Hg      |
| `chol`        | Serum cholesterol                         | Feature| Integer     | mg/dl      |
| `fbs`         | Fasting blood sugar > 120 mg/dl           | Feature| Categorical | -          |
| `restecg`     | Resting electrocardiographic results      | Feature| Categorical | -          |
| `thalach`     | Maximum heart rate achieved               | Feature| Integer     | -          |
| `exang`       | Exercise induced angina                   | Feature| Categorical | -          |
| `oldpeak`     | ST depression induced by exercise relative to rest | Feature | Float | -      |
| `slope`       | Slope of the peak exercise ST segment     | Feature| Categorical | -          |
| `ca`          | Number of major vessels (0-3) colored by fluoroscopy | Feature | Integer | - |
| `thal`        | Thallium stress test result               | Feature| Categorical | -          |
| `status`      | Diagnosis of heart disease                | Target | Categorical | -          |

This dataset will be used to analyze and predict heart disease presence in patients. The models developed in this project aim to support risk analysis and predictive insights in the healthcare sector.

## Project Goals
- Develop machine learning models to predict heart disease risk.
- Analyze feature importance and risk factors associated with heart disease.
- Use data-driven insights to assist healthcare professionals in patient assessment.

## Setup Instructions

1. Clone the Repository
   ```bash
   git clone https://github.com/Johnnysnipes90/Heart-Disease-Prediction.git
   cd Heart-Disease-Prediction

   cd Heart-Disease-Prediction

2. Create Virtual Environment
   source venv/Scripts/activate  # Activate on Windows
3. Install Dependencies
   pip install -r requirements.txt
4. After setting up, run the code in src/ to preprocess data, train models, and evaluate performance.


Usage
This project is designed to assist data coordinators, data scientists, and healthcare professionals in leveraging machine learning for health-related risk prediction. Follow the Jupyter notebooks and scripts provided in notebooks/ and src/ folders for data exploration, feature engineering, model training, and analysis.
