#  Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project develops an end-to-end machine learning pipeline to predict the presence of heart disease using clinical patient data. Multiple machine learning algorithms are trained, evaluated, and optimized to identify the best-performing model.

The project demonstrates industry-standard machine learning practices including preprocessing pipelines, cross-validation, hyperparameter tuning, and model evaluation.

---

## 🎯 Objectives

- Predict heart disease from patient attributes.
- Compare multiple machine learning algorithms.
- Optimize model performance using hyperparameter tuning.
- Evaluate models using robust metrics.

---

## 📂 Dataset

- Dataset: UCI Heart Disease Dataset
- Number of samples: 920
- Target variable: `heart_disease`

Features include:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Angina
- ST Depression
- ST Slope

---

## ⚙️ Machine Learning Workflow

1. Data Cleaning and Preprocessing
2. Handling Missing Values
3. Feature Scaling
4. Categorical Encoding
5. Train-Test Split
6. Stratified Cross Validation
7. Model Training
8. Hyperparameter Tuning
9. Performance Evaluation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn

---

## 🤖 Models Implemented

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- LightGBM Classifier
- CatBoost Classifier

---

## 🔄 Cross Validation

The project uses:

- Stratified K-Fold Cross Validation (`n_splits=5`)
- RandomizedSearchCV for hyperparameter tuning

---

## 📊 Evaluation Metrics

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

---

## 🏗️ Preprocessing Pipeline

The project implements Scikit-Learn Pipelines and ColumnTransformer to avoid data leakage and ensure reproducible workflows.

Components include:

- SimpleImputer
- StandardScaler
- OneHotEncoder
- ColumnTransformer
- Pipeline

---

## 🚀 How to Run

Clone the repository:

```bash
git clone <repository-url>
cd Heart-Disease-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📈 Results

The best-performing model was selected based on ROC-AUC score after hyperparameter tuning and cross-validation.

---

## 👨‍💻 Author

P Durgashyamanth

GitHub: https://github.com/your-username
