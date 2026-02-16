# Employee Attrition Prediction using Logistic Regression

## :pushpin: Project Overview

Employee attrition is a major concern for organizations as high turnover leads to increased recruitment costs, reduced productivity, and loss of experienced talent.

This project uses **Logistic Regression**, a supervised machine learning algorithm, to predict whether an employee is likely to leave the company based on various features such as age, job role, salary, job satisfaction, and work environment factors.

The objective is to help HR departments make data-driven decisions to improve employee retention.

---

## :dart: Objectives

- Perform Exploratory Data Analysis (EDA) on employee data
- Identify key factors contributing to employee attrition
- Build and train a Logistic Regression model
- Evaluate model performance using classification metrics
- Provide insights to reduce employee turnover

---

## :hammer_and_wrench: Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## :open_file_folder: Project Structure

```
Employee-Attrition-Prediction
├── Employee_Attrition_Logistic_Regression.ipynb
├── dataset.csv
└── README.md
```

## :bar_chart: Dataset Description

The dataset includes employee-related attributes such as:

- Age
- Gender
- Department
- Job Role
- Monthly Income
- Years at Company
- Job Satisfaction
- Work-Life Balance
- Overtime
- Attrition (Target Variable)

### Target Variable:
- `Attrition = Yes` → Employee left the company
- `Attrition = No` → Employee stayed in the company

---

## :mag_right: Project Workflow

### :one: Data Preprocessing
- Load dataset
- Handle missing values
- Encode categorical variables
- Feature scaling (if required)

### :two: Exploratory Data Analysis (EDA)
- Attrition distribution analysis
- Correlation heatmap
- Visualization of important features

### :three: Model Building
- Split data into training and testing sets
- Train Logistic Regression model

### :four: Model Evaluation
- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- ROC-AUC Curve

---

## :chart_with_upwards_trend: Model Performance

The Logistic Regression model was evaluated using classification metrics and confusion matrix to measure prediction performance.

The model helps identify key drivers of employee attrition and can assist HR in proactive retention strategies.

---

## :pushpin: Key Insights
Overtime employees show higher attrition rates.
Lower job satisfaction increases probability of leaving.
Monthly income and years at company influence retention.
Work-life balance plays a significant role in employee stability.

## :crystal_ball: Future Improvements
Apply advanced models (Random Forest, XGBoost)
Hyperparameter tuning
Handle class imbalance using SMOTE
Deploy model using Flask or Streamlit
Create an interactive dashboard
