# 🚢 Titanic Survival Prediction Machine Learning Project

## 📌 Overview
This project predicts passenger survival on the Titanic using machine learning. It analyzes various passenger attributes to determine survival likelihood with **82% accuracy**.

## 🔍 Key Features
- **Data Analysis**: Explore survival patterns by gender, class, age
- **Feature Engineering**: Created family size and alone status features
- **ML Model**: Random Forest classifier implementation
- **Model Evaluation**: Accuracy metrics and feature importance
- **Prediction System**: Predict survival for new passenger data

🚀 Usage
Run Jupyter Notebook:
jupyter notebook notebooks/Titanic_Survival_Prediction.ipynb

📊 Dataset
Contains records for 891 passengers with:

Survival status (0 = Died, 1 = Survived)

Passenger class (1st, 2nd, 3rd)

Name, Age, Sex

Siblings/Spouses
Parents/Children
Ticket, Fare, Cabin

data: Titanic-Dataset.csv

📈 Results
Metric	Score
Accuracy	82%
Precision	0.83
Recall	0.80
F1-Score	0.81
Top Predictive Features:

Gender (♀ 74% survival vs ♂ 19%)

Passenger Class (1st: 63%, 2nd: 47%, 3rd: 24%)

Age (Children <10: 59% survival)
