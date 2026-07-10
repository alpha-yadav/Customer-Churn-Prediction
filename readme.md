# Customer Churn Prediction

A Machine Learning project that predicts whether a telecom customer is likely to churn using classification algorithms.

---

## Overview

Customer churn prediction helps telecom companies identify customers who are likely to leave their service. By predicting churn early, businesses can improve customer retention through targeted offers and better support.

This project compares multiple Machine Learning models and selects the best-performing model based on evaluation metrics.

---

##  Features

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling
- Model Training
- Model Evaluation
- Model Comparison
- Saved Trained Models
- Prediction Support

---

##  Project Structure

```text
Customer_Churn/
│
├── config/
│   └── logic_config.json
│
├── data/
│   └── Telecom_data.csv
│
├── img/
│   ├── decision_tree.png
│   └── gender-churn.png
│
├── model/
│   ├── logic_model.npy
│   └── svc_model.npy
│
├── src/
│
├── main.ipynb
│
├── test.py
│
└── README.md
```

---

# Dataset

Dataset contains customer information such as

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Device Protection
- Streaming Services
- Contract
- Payment Method
- Monthly Charges
- Total Charges

Target Variable

```
Churn
```

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

#  Machine Learning Models

The following models were trained and evaluated.

- Logistic Regression
- Decision Tree Classifier
- Support Vector Classification (SVC)

---

# Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| Logistic Regression | 82% | 69% | 60% | 64% |
| Decision Tree | 81% | **72%** | 49% | 58% |
| Support Vector Classification | **82%** | 69% | **61%** | **65%** |

---

# Best Model

Support Vector Classification (SVC)

Reason

- Highest F1 Score
- Highest Recall
- Same Accuracy as Logistic Regression
- Better overall balance between Precision and Recall

---

# Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# Visualizations

- Gender vs Churn
- Decision Tree Visualization

---

# Run Project

Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Notebook

```bash
jupyter notebook main.ipynb
```

or

```bash
python test.py
```

---

#  Future Improvements

- Random Forest
- XGBoost
- Hyperparameter Tuning
- Cross Validation
- Streamlit Web Application
- Flask REST API
- Docker Deployment

---

#  Author

Aditya Yadav

