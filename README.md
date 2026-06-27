# Diabetes Prediction Using Machine Learning

## Project Overview

This project develops and evaluates several machine learning models to predict whether a patient has diabetes based on clinical measurements from the Pima Indians Diabetes Dataset. The primary objective is to compare the performance of different classification algorithms and identify the most effective model for diabetes prediction.

## Dataset

The project uses the **Pima Indians Diabetes Dataset**, which contains **768 patient records**, **8 numerical features**, and one binary target variable (`Outcome`).

The input features include:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- Body Mass Index (BMI)
- Diabetes Pedigree Function
- Age

The target variable indicates whether the patient has diabetes (`1`) or not (`0`).

## Project Workflow

The project consists of the following stages:

1. Load and explore the dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Handle invalid zero values by replacing them with the median of non-zero observations.
4. Split the dataset into training (80%) and testing (20%) sets.
5. Standardize features for scale-sensitive algorithms.
6. Train multiple machine learning models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)
   - XGBoost
7. Evaluate model performance using:
   - Accuracy
   - F1-Score
   - Sensitivity (Recall)
   - Specificity
   - ROC-AUC
8. Compare all models using performance metrics, confusion matrices, and ROC curves.
9. Select the best-performing model and discuss the results.

## Results

The experimental results show that tree-based models outperform the linear model on this dataset. Among the evaluated algorithms, the **Decision Tree** achieved the best balance between Accuracy, F1-Score, and Sensitivity, while **XGBoost** obtained the highest ROC-AUC, demonstrating excellent discrimination capability.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Repository Contents

- `Diabetes Prediction.ipynb` – Complete project implementation
- `diabetes.csv` – Dataset
- `README.md` – Project documentation
- Figures and evaluation results

## Author

This project was developed for educational purposes to demonstrate the application of machine learning techniques for medical diagnosis and comparative model evaluation.
