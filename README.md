# AI & ML Task 5 – Ensemble Learning & Model Optimization

## 📌 Project Overview

This project is part of my **Artificial Intelligence & Machine Learning internship – Task 5**.

The main objective of this task is to build and compare different machine learning classification models, optimize an ensemble model using GridSearchCV, and select the best final model based on performance and stability.

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin dataset** available through Scikit-learn.

- Total Samples: 569
- Features: 30
- Problem Type: Binary Classification
- Training Data: 80%
- Testing Data: 20%

## 🤖 Models Used

### 1. Logistic Regression

Logistic Regression is used as the baseline classification model.

### 2. Random Forest

Random Forest is used as an ensemble learning model based on multiple decision trees.

### 3. Gradient Boosting

Gradient Boosting is used as a boosting-based ensemble model.

## 📈 Model Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | **98.25%** | **98.61%** | **98.61%** | **98.61%** |
| Random Forest | 95.61% | 95.89% | 97.22% | 96.55% |
| Gradient Boosting | 95.61% | 94.67% | 98.61% | 96.60% |

## ⚙️ Hyperparameter Tuning

Random Forest was optimized using **GridSearchCV**.

Parameters tested:

```text
n_estimators = [50, 100]
max_depth = [3, 5, 7]

🔄 Cross-Validation
A 5-Fold Stratified Cross-Validation was performed to check model stability and reliability.
The models were compared using:
Mean Accuracy
Accuracy Standard Deviation
Mean F1-Score
F1 Standard Deviation
📌 Evaluation Techniques

The following evaluation methods were used:
Accuracy
Precision
Recall
F1-Score
Classification Report
Confusion Matrix
GridSearchCV
5-Fold Cross-Validation
📁 Project Files
AI-ML-Task-5/
│
├── AI_ML_Task_5_Complete.ipynb
├── AI_ML_Task_5_Full_Report.pdf
├── Task_5_Model_Comparison.csv
├── Task_5_Model_Comparison_Chart.png
├── Task_5_Confusion_Matrix.png
├── README.md
└── requirements.txt

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Jupyter Notebook

▶️ How to Run
Install the required libraries:
pip install pandas numpy matplotlib scikit-learn jupyter

Open the notebook:
jupyter notebook AI_ML_Task_5_Complete.ipynb

Run the notebook cells from top to bottom.

🎓 Key Learning Outcomes

Through this project, I learned about:

Ensemble Learning
Random Forest
Gradient Boosting
Logistic Regression
Hyperparameter Tuning
GridSearchCV
Cross-Validation
Model Comparison
Classification Metrics
Confusion Matrix
Model Selection

👨‍💻 Author
Naveen kumar
B.Tech – Computer Science & Engineering
AI & Data Science
AI & ML Internship at Maincrafts Technology
