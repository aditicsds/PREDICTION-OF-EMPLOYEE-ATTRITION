# PREDICTION-OF-EMPLOYEE-ATTRITION

This project is focused on predicting employee attrition using machine learning techniques. It helps organizations identify employees at risk of leaving by analyzing patterns in historical employee data, including performance, job satisfaction, compensation, and work-life balance.

---

### Table of Contents

* Overview
* Problem Statement
* Objectives
* Key Goals
* Technology Stack
* System Architecture
* Dataset Details
* Design Diagrams
* Model Workflow
* Project Author

---

### Overview

Predicting employee attrition helps organizations prevent unwanted turnover. By studying factors like job satisfaction, demographics, and work performance, this project builds a predictive system that supports HR decision-making and strategic workforce planning.

---

### Problem Statement

High employee turnover increases costs, disrupts teams, and affects performance. Without a predictive approach, organizations react too late to retention problems. This project builds a model to forecast attrition and helps HR teams take proactive steps.

---

### Objectives

* Analyze employee data to identify patterns leading to attrition.
* Predict the likelihood of an employee leaving.
* Enable preemptive retention efforts through early risk identification.

---

### Key Goals

* Identify at-risk employees for early intervention.
* Base HR decisions on data-driven insights.
* Reduce recruitment and training costs.
* Improve employee engagement and satisfaction.
* Provide custom retention strategies for different employees.
* Enable stable teams and long-term planning.

---

### Technology Stack

* Language: Python
* Libraries: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
* Tools: Jupyter Notebook / VS Code

---

### System Architecture

```
HR Data -> Preprocessing -> Feature Selection -> Model Training -> Prediction -> Dashboard Output
```

---

### Dataset Details

The dataset includes:

* Demographics: Age, Gender, Marital Status
* Job Info: Job Role, Level, Satisfaction, Work-Life Balance
* Performance & Pay: Ratings, Income, Stock Options
* Environment: Department, Travel, Satisfaction
* Attrition: Yes/No labels (target variable)

Key tasks include:

* Data Cleaning (handling missing values)
* Feature Engineering (creating new inputs)
* Encoding (categorical to numeric)
* Normalization (scaling values)

---

### Design Diagrams

* 0-Level DFD: Shows employee data input to prediction output.
* 1-Level DFD: Includes preprocessing, feature selection, model training, and reporting.
* Use Case Diagram: HR/Admin/System roles and interactions.
* Sequence Diagram: Order of processes from data collection to report generation.

---

### Model Workflow

* Classification Algorithms: Logistic Regression, Decision Tree, Random Forest, XGBoost
* Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC
* Optimization: Hyperparameter tuning via Grid Search / Random Search

---

### Project Author

| Name         | Role                         |
| ------------ | ---------------------------- |
| Aditi Tiwari | Coding, Design, Presentation |

---
