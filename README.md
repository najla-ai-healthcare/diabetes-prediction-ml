# Diabetes-Prediction-ML
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/najla-ai-healthcare/diabetes-prediction-ml/blob/main/Diabetes-Prediction-ML.ipynb)
Machine Learning model to predict diabetes risk using patient clinical data

## Overview
This project uses **Machine Learning** to predict the likelihood of diabetes based on patient data such as age, BMI, and medical history.

## Dataset
The dataset used in this project is sourced from **Kaggle**. It contains clinical data from patients and includes the following key features:
* **Glucose**: Plasma glucose concentration.
* **Blood Pressure**: Diastolic blood pressure (mm Hg).
* **BMI**: Body mass index (weight in kg/(height in m)^2).
* **Insulin**: 2-Hour serum insulin (mu U/ml).
* **Age**: Age of the patient.
* **Pregnancies**: Number of times pregnant.
* **Diabetes Pedigree Function**: Diabetes likelihood based on family history.

## Technologies Used
* Python
* Pandas & NumPy (Data Processing)
* Scikit-Learn (Machine Learning)
* Matplotlib/Seaborn (Visualization)

## How to Run
1. Open the notebook in **Google Colab**.
2. Run all cells to see the data analysis and model training.

## Results
The performance of different algorithms is summarized below:

| Algorithm | Accuracy |
| :--- | :---: |
| **Logistic Regression** | **78%** |
| Random Forest | 72% |
| KNeighbors | 69% |

## Key Findings (Feature Importance)
The analysis shows that **Glucose levels**, **BMI**, and **Age** are the strongest predictors of diabetes in this dataset. This aligns with medical research where metabolic factors play a primary role.

1. ** Glucose ** ( most significant)
2. ** BMI **
3. ** Age **
4. ** Diabetes Pedigree Function ** 
5. **Blood Pressure**
6. **Pregnancies**
7. **Insulin**
8. **Skin Thickness**

