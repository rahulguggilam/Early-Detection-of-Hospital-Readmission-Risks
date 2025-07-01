# 🏥 Early Detection of Hospital Readmission Risks

This project uses machine learning to predict whether a patient will be readmitted to the hospital within 30 days. We apply **Logistic Regression** and fine-tune it using **GridSearchCV** to improve prediction accuracy. Early identification of high-risk patients can help improve healthcare outcomes and reduce costs.

## 📌 Overview

- **Model Used**: Logistic Regression
- **Tuning Method**: GridSearchCV
- **Goal**: Predict hospital readmission within 30 days
- **Techniques**: Data Cleaning, Feature Engineering, Model Training, Evaluation

## 📁 Project Files

- `hospitaldata.csv` – Raw data set
- `EDA.ipynb` – Explore data distributions, correlations, and key patterns.

- `README.md` – Project documentation.

## 📊 Dataset

The dataset includes hospital records for patients with the following types of features:

- Patient demographics (e.g., age, gender)
- Clinical measurements (e.g., number of diagnoses, lab procedures)
- Hospital data (e.g., time in hospital, discharge type)
- Readmission status (target variable)

> The dataset is preloaded in the notebooks. You can modify the data path inside the code if needed.

## 🚀 How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/rahulguggilam/Early-Detection-of-Hospital-Readmission-Risks.git
cd Early-Detection-of-Hospital-Readmission-Risks
