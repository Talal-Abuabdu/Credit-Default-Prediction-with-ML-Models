# Credit Default Prediction using Machine Learning

This project presents an end-to-end supervised learning pipeline for predicting loan default status using financial and demographic features. The goal is to help financial institutions reduce risk and improve decision-making efficiency through accurate, interpretable, and tunable models.

## Models Used

- Logistic Regression (baseline model)  
- Random Forest (best performer)  
- Neural Network (competitive deep learning model)

## Features

- Median imputation for missing values  
- Outlier handling via IQR and median replacement  
- Categorical encoding (Label and One-Hot Encoding)  
- Feature scaling with StandardScaler  
- Hyperparameter tuning using GridSearchCV  
- Evaluation using Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC  
- Visualizations including heatmaps, ROC curves, and confusion matrices

## Results Snapshot

| Model             | Accuracy | Precision (1) | Recall (1) | F1-score (1) | ROC AUC |
|------------------|----------|---------------|------------|--------------|---------|
| Logistic Regression | 87.0%   | 0.74          | 0.57       | 0.64         | ~0.84   |
| Random Forest       | 93.3%   | 0.95          | 0.71       | 0.81         | ~0.97   |
| Neural Network      | 92.2%   | 0.92          | 0.68       | 0.78         | ~0.95   |

## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn  
- Jupyter / Google Colab

## How to Run

Open and run `CWFinal.ipynb` using Google Colab
