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
- Random State: 42

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

## 📊 Model Performance

The models were compared using Accuracy, Precision, Recall, and F1-Score.

**Logistic Regression achieved the best overall performance** among the three models.

## ⚙️ Hyperparameter Tuning Using GridSearchCV

Random Forest was optimized using **GridSearchCV**.

The following parameters were tested:

- `n_estimators`: 50, 100
- `max_depth`: 3, 5, 7
- Cross-validation: 3 folds
- Scoring metric: F1-Score

## 🏆 Best Hyperparameters

The best hyperparameters obtained from GridSearchCV were:

- `n_estimators = 100`
- `max_depth = 5`

Best Cross-Validation F1-Score:

**0.9633**

## 🎯 Final Optimized Random Forest

The optimized Random Forest achieved the following results on the test dataset:

- Accuracy: **95.61%**
- Precision: **95.89%**
- Recall: **97.22%**
- F1-Score: **96.55%**

## 🔄 Cross-Validation

A **5-Fold Stratified Cross-Validation** was performed to check model stability and reliability.

The models were compared using:

- Mean Accuracy
- Accuracy Standard Deviation
- Mean F1-Score
- F1 Standard Deviation

Logistic Regression showed the strongest overall cross-validation performance among the compared models.

## 📌 Evaluation Techniques

The following evaluation techniques were used:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix
- GridSearchCV
- 5-Fold Cross-Validation

## 📁 Project Files

The repository contains the following files:

- `AI_ML_Task5.ipynb` – Complete Python/Jupyter Notebook
- `AI_ML_Task_5_Full_Report(1).pdf` – Detailed project report
- `Task_5_Model Performance Comparison.png` – Model performance visualization
- `Task_5_Confusion_Matrix.png` – Confusion matrix visualization
- `README.md` – Project documentation
- `requirements.txt` – Required Python libraries

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/nvn05/AI-ML-Task-5-Ensemble-Learning.git
cd AI-ML-Task-5-Ensemble-Learning
pip install pandas numpy matplotlib scikit-learn jupyter
jupyter notebook AI_ML_Task_5_Complete.ipynb

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
