# Predictive-Analysis-Project-Final
# Medical Outcome Prediction Project

# Project Summary
This project applies machine learning models to predict medical outcomes (positive or negative) using patient health metrics. The goal is to support early diagnosis and targeted interventions by identifying key indicators of potential health risks.

# Objectives
- Analyze real-world health data to uncover meaningful patterns.
- Build and evaluate predictive models (Logistic Regression and Random Forest).
- Identify the most influential features affecting medical outcomes.
- Develop a tool that can support proactive medical decision-making.

#Dataset Description
- **File Name**: `Medicaldataset.csv`  
- **Features**: Age, Gender, Heart Rate, Systolic BP, Diastolic BP, Blood Sugar, CK-MB, Troponin, Outcome  
- **Target Variable**: Outcome (Positive or Negative)  
- **Source**: Provided as part of academic coursework (not from a public repository).

# Tools & Libraries Used
- Python (Google Colab)
- `pandas`, `numpy` – Data cleaning and transformation
- `matplotlib`, `seaborn` – Visualization
- `scikit-learn` – Modeling, preprocessing, and evaluation
- `StandardScaler` – Feature scaling
- `LogisticRegression`, `RandomForestClassifier` – Predictive modeling

## ▶️ How to Run This Project

1. **Open the Colab Notebook**
https://colab.research.google.com/drive/1EK09eR0XCPvjBET9HCcaXUDUmwQ1qgW6#scrollTo=anP0XJJzi4ZF
2. **Steps to Run**:
   - Upload `Medicaldataset.csv` to your Colab session.
   - Run the cells in order to:
     - Load and clean the dataset
     - Explore the data through visualizations
     - Train and evaluate the Logistic Regression and Random Forest models
     - View model performance metrics and feature importance

3. **Output**:
   - Visual insights from data exploration
   - Classification reports and confusion matrices
   - Final business insights and recommendations
