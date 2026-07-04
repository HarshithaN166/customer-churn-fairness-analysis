# Customer Churn Prediction: Fairness, Bias & Explainable AI

## Overview

This project focuses on building a Customer Churn Prediction model while ensuring fairness, transparency, and responsible AI practices.

The model is trained using a Random Forest Classifier and analyzed using Explainable AI (XAI) techniques such as SHAP and LIME. Bias detection is performed on sensitive attributes, followed by fairness improvement using SMOTE.

---

## Objectives

- Predict customer churn using Machine Learning
- Explain model predictions using SHAP and LIME
- Detect bias across sensitive demographic groups
- Evaluate fairness metrics
- Reduce model bias through mitigation techniques
- Demonstrate Responsible AI principles

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SHAP
- LIME
- Imbalanced-learn (SMOTE)

---

## Project Structure

```
.
├── customer_churn_data.csv
├── task3.ipynb
├── fairness_analysis.md
├── requirements.txt
├── screenshot 1.png
├── Screenshot 2.png
└── README.md
```

---

## Dataset

The project uses the **Telco Customer Churn Dataset**, containing customer information such as:

- Gender
- Senior Citizen
- Contract Type
- Monthly Charges
- Tenure
- Internet Services
- Payment Method

Target Variable:

- Churn (Yes/No)

Sensitive attributes used for fairness evaluation:

- Gender
- Senior Citizen

---

## Machine Learning Model

- Random Forest Classifier

The notebook performs:

- Data preprocessing
- Feature encoding
- Train/Test split
- Model training
- Prediction
- Performance evaluation

---

## Explainable AI (XAI)

### SHAP

SHAP provides global explanations by showing:

- Feature importance
- Feature impact
- Summary plots
- Bar plots
- Force plots

---

### LIME

LIME explains individual predictions by identifying the most influential features contributing to a specific prediction.

---

## Fairness Analysis

The model is evaluated across demographic groups using metrics including:

- Accuracy
- False Positive Rate (FPR)
- True Positive Rate (TPR)
- Prediction Rate

Sensitive Groups:

- Gender
- Senior Citizen

This helps identify any unfair behavior in the model.

---

## Bias Mitigation

SMOTE (Synthetic Minority Oversampling Technique) is used to reduce bias by balancing the training data.

Results show:

- Reduced disparity in False Positive Rate
- Improved fairness across groups
- Stable overall model accuracy

---

## Project Outputs

- Customer Churn Prediction
- Feature Importance Analysis
- SHAP Summary Plot
- SHAP Bar Plot
- SHAP Force Plot
- LIME Local Explanation
- Fairness Metrics
- Bias Comparison Charts
- Fairness Analysis Report

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-fairness-analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Project

Open the notebook:

```
task3.ipynb
```

Run all cells sequentially to generate:

- Predictions
- SHAP explanations
- LIME explanations
- Fairness metrics
- Bias mitigation results

---

## Key Concepts Demonstrated

- Explainable AI (XAI)
- Responsible AI
- Machine Learning Fairness
- Bias Detection
- Bias Mitigation
- Customer Churn Prediction
- Model Interpretability

---

## Results

The project demonstrates that integrating Explainable AI and fairness evaluation improves transparency and helps identify demographic disparities. Applying SMOTE reduces bias while maintaining strong predictive performance.

---

## Future Improvements

- Fairlearn Integration
- Adversarial Debiasing
- Threshold Optimization
- Deep Learning Models
- Real-time Prediction Dashboard
- Deployment using Flask or Streamlit

---

## Author

Harshitha
