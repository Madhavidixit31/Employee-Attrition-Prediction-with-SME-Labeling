# SME-Driven Employee Attrition Prediction Project

This project aims to predict which employees are likely to leave a company using machine learning. The approach involves SME-driven data labeling, clustering, feature engineering, and model evaluation.

---

## 📌 Problem Statement
The goal is to develop a machine learning model to identify which employees are likely to leave the company. The dataset provided contains anonymized employee features without departure labels. Limited queries to a virtual SME (John) are allowed to label a subset of the data for training purposes.

---

## 🛠 Key Features
**Data Source**: [Employee dataset from UMBC Data Science repository](https://raw.githubusercontent.com/msaricaumbc/DS_data/master/ds602/final/employee_departure_dataset_X.csv)

**Techniques Used**:
- Python (pandas, scikit-learn, matplotlib)
- Data preprocessing and cleaning
- Feature engineering
- SMOTE for class imbalance
- Ensemble models (Random Forest, Gradient Boosting)
- Model evaluation using F1-score and ROC AUC
- Model serialization with joblib

---

## ✨ Project Highlights
- Performed clustering on employee data for representative sampling.
- Collected labels from SMEs to guide model training.
- Trained classification models to predict attrition risk.
- Evaluated models for precision, recall, and overall performance.

---

## Structure
This repository includes:
- Jupyter notebook with the full analysis and modeling pipeline
- Final trained model for inference

---

### How to Run
1. Clone this repository.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter notebook and follow the code cells.
