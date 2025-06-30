# Heart Disease Prediction  
## Elevate Labs AI/ML Internship — Task 5  
**By:** Harsimran Singh  
**Date:** 30 June 2025  

---

## Project Overview

This project focuses on predicting the presence of heart disease using supervised machine learning techniques:

- Decision Tree Classifier  
- Post-Pruned Decision Tree  
- Random Forest Classifier  

The dataset used is the classic Heart Disease Dataset, containing relevant health metrics of patients.

---

## Dataset Summary

| Feature       | Description                               |
|---------------|-------------------------------------------|
| age           | Age of the patient                        |
| sex           | Gender (1 = Male, 0 = Female)             |
| cp            | Chest pain type                           |
| trestbps      | Resting blood pressure                    |
| chol          | Serum cholesterol (mg/dl)                 |
| fbs           | Fasting blood sugar > 120 mg/dl           |
| restecg       | Resting electrocardiographic results      |
| thalach       | Maximum heart rate achieved               |
| exang         | Exercise-induced angina                   |
| oldpeak       | ST depression induced by exercise         |
| slope         | Slope of the peak exercise ST segment     |
| ca            | Number of major vessels (0-3)             |
| thal          | Thalassemia indicator                     |
| target        | Heart disease presence (1 = Yes, 0 = No)  |

---

## Project Workflow

- Data Cleaning and Null Value Check  
- Exploratory Data Analysis (Correlation Heatmap)  
- Feature Scaling using StandardScaler  
- Train-Test Split (70% Training, 30% Testing)  
- Decision Tree Classifier  
- Applied Post-Pruning to improve generalization  
- Visualized Decision Tree structure  
- Random Forest Classifier for higher accuracy and robustness  
- Feature Importance analysis using Random Forest  
- Cross-validation for reliable performance estimation  
- Individual tree visualization from Random Forest ensemble  

---

## Key Results

| Model                   | Accuracy  |
|-------------------------|-----------|
| Decision Tree (Basic)   | Achieved decent accuracy, risk of overfitting |
| Decision Tree (Pruned)  | Improved generalization using max_depth=7 |
| Random Forest           | High accuracy (~98%), reduced overfitting |

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Visualizations Included

- Correlation Heatmap  
- Decision Tree Structure  
- Random Forest Feature Importance  
- Individual Decision Tree from Random Forest  

---

## Conclusion

- Decision Trees provide easy interpretability but require pruning to avoid overfitting  
- Random Forest improves performance using ensemble learning and randomness  
- Feature importance highlights key medical factors influencing heart disease prediction  

---

## Author

**Harsimran Singh**  
Elevate Labs AI/ML Internship - Task 5 Submission  
