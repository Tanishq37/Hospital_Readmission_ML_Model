# 🏥 Hospital Readmission Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether a diabetic patient will be readmitted to the hospital using machine learning techniques. Early identification of high-risk patients can help hospitals reduce treatment costs, improve patient care, and optimize healthcare resources.

The project uses real-world healthcare data containing patient demographics, diagnoses, medications, hospital visits, and treatment history.

## 🎯 Business Objective
Hospital readmissions are expensive and often preventable.

The goal of this project is to build a machine learning model that predicts patient readmission risk so healthcare providers can take preventive action.

## 📂 Dataset Details
- Dataset: Diabetic Patient Readmission Dataset  
- Total Records: 100,000+ rows  
- Domain: Healthcare Analytics  
- Format: CSV  
- Notebook Used: `HospitalReadmission_Final.ipynb`

### Target Variable
Original values:
- `NO` = No readmission  
- `<30` = Readmitted within 30 days  
- `>30` = Readmitted after 30 days  

Converted into Binary Classification:
- `0` = No Readmission  
- `1` = Readmission

## 🛠 Tech Stack
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  
- Joblib  
- Jupyter Notebook

## 🔄 Project Workflow

### 1️⃣ Data Cleaning
- Replaced `?` values with null values  
- Removed columns with excessive missing values  
- Checked duplicate rows  
- Handled categorical features

### 2️⃣ Exploratory Data Analysis (EDA)
Analyzed important patterns such as:
- Age vs Readmission  
- Gender vs Readmission  
- Insulin Usage vs Readmission  
- Hospital Stay Duration vs Readmission

### 3️⃣ Feature Selection
Used Random Forest feature importance to identify top predictors.

### 4️⃣ Model Building
Built and compared multiple machine learning models:
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier

### 5️⃣ Model Validation
Applied Cross Validation to test model consistency.

## 📊 Model Performance

| Model | Accuracy |
|------|----------|
| Logistic Regression | 61.75% |
| Random Forest | 63.16% |
| XGBoost | **64.57%** |

### Cross Validation Score
- Mean Accuracy: **64.26%**

## 🏆 Best Model
### XGBoost Classifier

## 📈 Key Business Insights
- Patients with more lab procedures showed higher readmission risk  
- Longer hospital stays were linked with readmissions  
- Patients with prior inpatient visits were more likely to return  
- Higher medication counts indicated more complex health conditions  
- Age influenced readmission probability

## 💼 Resume Highlights
- Developed healthcare machine learning project using 100K+ hospital records  
- Built predictive model for hospital readmission risk  
- Improved performance using XGBoost and feature selection  
- Validated model stability using cross-validation  
- Generated actionable insights for healthcare decision-making

## 🚀 How to Run Project

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
jupyter notebook
```

Open `HospitalReadmission_Final.ipynb`

## 📁 Project Files
- `HospitalReadmission_Final.ipynb`
- `diabetic_data.csv`
- `README.md`

## 👤 Author
**Tanishq Arora**
