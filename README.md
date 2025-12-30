# Diabetes-Prediction-ML

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/najla-ai-healthcare/diabetes-prediction-ml/blob/main/Diabetes-Prediction-ML.ipynb)

Machine Learning model to predict diabetes risk using patient clinical data.

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
* **Skin Thickness**: Triceps skin fold thickness (mm).

## Technologies Used
* **Python**
* **Pandas & NumPy** (Data Processing)
* **Scikit-Learn** (Machine Learning)
* **Matplotlib & Seaborn** (Visualization)

## Results
The performance of different algorithms is summarized below:

| Algorithm | Accuracy |
| :--- | :---: |
| **Logistic Regression** | **78%** |
| Random Forest | 72% |
| KNeighbors | 69% |

### Visual Analysis
| Feature Importance | ROC Curve Comparison |
| :---: | :---: |
| ![Feature Importance](plot1.png) | ![ROC Curve Comparison](plot2.png) |

#### ROC Curve Comparison
The ROC Curve Comparison plot evaluates the performance of different models (Logistic Regression, Random Forest, and KNeighbors) simultaneously. 
* **Comparison Insight:** By comparing the **AUC (Area Under the Curve)** of each model, we can see that **Logistic Regression** covers more area toward the top-left corner, making it the most reliable model for diabetes screening.
* **Clinical Significance:** A higher AUC means the model has a better chance of distinguishing between patients with and without diabetes, minimizing both false positives and false negatives.

#### Feature Importance Analysis
The bar plot confirms that metabolic factors play a primary role in prediction. This ranking aligns with clinical expectations, as insulin resistance and body mass are primary indicators of diabetic risk:
1. **Glucose** (Most significant)
2. **BMI**
3. **Age**
4. **Diabetes Pedigree Function**
5. **Blood Pressure**
6. **Pregnancies**
7. **Insulin**
8. **Skin Thickness**

## How to Run
1. Click the **Open In Colab** badge at the top of this page.
2. Run all cells to see the data analysis and model training.


