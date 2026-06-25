# Customer Retention Prediction

![Python](https://img.shields.io/badge/Python-Programming-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)

Machine learning project developed to predict whether a customer will return to an e-commerce platform.

Created by [Karla Roman](https://github.com/karla-roman)

---

## Project Overview

Customer retention is an important business metric because keeping existing customers is usually less expensive than acquiring new ones.

The goal of this project was to prepare customer data, train different machine learning models, and compare their performance to predict customer retention.

---

## Dataset

The dataset contains customer information used to predict whether a customer will return.

| Attribute | Description |
|-----------|-------------|
| `age` | Customer age |
| `total_spent` | Customer spending |
| `marketing_engaged` | Customer response to marketing campaigns |
| `gender` | Customer gender |

> **Note:** The analysis notebook is written in Spanish because this project was developed for an academic context in Mexico.

---

## Solution Workflow

```text
Dataset
    │
    ▼
Data Exploration
    │
    ▼
Data Preprocessing
    │
    ├── Encoding
    └── Feature Scaling
    │
    ▼
Model Training
    │
    ├── Logistic Regression
    ├── Decision Tree
    └── Random Forest
    │
    ▼
Model Evaluation
    │
    ▼
Best Model Selection
```

---

## Model Development

The following machine learning models were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

The models were compared using classification metrics, and the best-performing model was selected after hyperparameter tuning with GridSearchCV.

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical analysis |
| Matplotlib | Data visualization |
| Scikit-learn | Machine learning |

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Classification Models
- Model Evaluation
- Hyperparameter Tuning
- Machine Learning
- Python

---

## Repository Structure

```text
customer-retention-prediction
│
├── README.md
├── synthetic_customer_data.csv
└── prediccion_retorno_clientes.ipynb
```

---

## Results

- Best model: Logistic Regression
- Test accuracy: 100%
- The confusion matrix showed perfect classification on the available dataset.

---

## Limitations

- The dataset is relatively small.
- Results may not generalize to real-world scenarios.
- Additional customer variables could improve model performance.

---

## Key Outcome

This project demonstrates a complete machine learning workflow, from data preparation and model training to evaluation and model selection using Python and Scikit-learn.
