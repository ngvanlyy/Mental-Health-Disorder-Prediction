# 🧠 Mental Health Disorder Prediction

**Python · Machine Learning · Classification · Scikit-learn**

A supervised machine learning project forecasting mental health disorders in students using demographic, academic, lifestyle and psychological factors.

## 🔗 Python Notebook

The complete machine learning implementation is available in Google Colab:

**[Open Python Notebook in Google Colab](https://colab.research.google.com/drive/1OofHFD95rMRJ_rC8daNrIjTs3JiBugWK?usp=sharing)**

The notebook contains the data preprocessing, feature engineering, SMOTE balancing, model training, hyperparameter optimisation and evaluation.

## 📌 Project Overview

The project investigates whether supervised machine learning can be used to forecast mental health disorders among students based on factors such as academic pressure, study satisfaction, financial stress, work/study hours and other personal and behavioural attributes.

The analysis uses the **Student Depression Dataset**, containing **27,901 student records and 18 attributes**.

The target variable is `Depression`:

- **0** → No
- **1** → Yes

## 🤖 Machine Learning

Three classification models were developed and compared:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

The workflow included:

- Data cleaning
- Binary and one-hot encoding
- Train/test splitting
- Feature scaling with `StandardScaler`
- Class balancing using **SMOTE**
- Correlation analysis
- Hyperparameter optimisation using `GridSearchCV`
- Model evaluation

## 📊 Results

| Model | Accuracy | Precision | Recall |
|---|---:|---:|---:|
| Decision Tree | 78.16% | 72.70% | **88.12%** |
| **Random Forest** | **80.95%** | **86.68%** | 81.99% |
| SVM | 80.92% | 81.94% | **86.68%** |

**Random Forest** achieved the highest accuracy and precision, while **SVM** achieved the highest recall among the final models.

## 🔍 Key Findings

- 📚 Academic Pressure showed the strongest reported correlation with depression (**0.47**).
- ⏱️ Work/Study Hours and Age showed weaker positive relationships.
- 😊 Study Satisfaction showed a weak negative relationship with depression.
- 🌲 Random Forest achieved the strongest overall accuracy and precision.
- ⚙️ SVM provided strong recall while maintaining similar overall accuracy.
- 🧠 The models are intended as predictive screening tools and not as clinical diagnostic systems.

## 🛠️ Tools

`Python` · `pandas` · `NumPy` · `scikit-learn` · `SMOTE` · `GridSearchCV` · `Machine Learning`

## 📁 Repository Structure

```text
Mental-Health-Disorder-Prediction/
│
├── README.md
├── report/
│   └── machine-learning-report.pdf
├── code/
│   └── mental-health-disorder-prediction.py
└── data/
    └── student-depression-dataset.csv
```

## 📄 Report

The full report contains the data preparation, exploratory analysis, feature analysis, model development, optimisation, evaluation and model comparison.

## 🎓 Project Outcome

This project demonstrates practical experience in **supervised machine learning, classification, feature preprocessing, imbalanced-data handling, hyperparameter optimisation and model evaluation**.
