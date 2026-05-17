# 🎓 Student Performance Prediction System
### Business Analyst Portfolio Project | EdTech Analytics | Flask Web App

---

## 🎯 Business Problem
Educational institutions lack early warning systems to identify at-risk students 
**before** they fail — leading to poor outcomes and high dropout rates. 
This project defines the requirements and delivers a working prediction system 
for academic administrators to intervene proactively.

## 👥 Stakeholders
| Stakeholder | Interest |
|---|---|
| Academic Administrators | Early identification of at-risk students |
| Faculty | Targeted support for struggling students |
| Students | Personalized performance feedback |
| Parents | Transparency in academic risk factors |

## 📋 My Role (Business Analyst Perspective)
- Defined functional requirements for the prediction system
- Identified KPIs: cognitive, interpersonal, verbal, and analytical skill scores
- Translated academic factors (GPA, SAT, study hours, home environment) into model features
- Designed the user-facing web interface requirements (Flask app)
- Reported insights in business language for non-technical administrators

## 📊 Model Performance Summary
| Model | Accuracy |
|---|---|
| Random Forest | **99.63%** |
| SVM (Linear) | **99.63%** |
| Decision Tree | **98.89%** |
| KNN | **96.67%** |

## 🔍 Key Features Analyzed
- GPA & SAT Score
- Study Hours Per Week
- Parent Education Level
- Extracurricular Participation
- Motivation Level & Home Environment
- Cognitive, Verbal, Analytical & Interpersonal Skills

## 🌐 System Delivered
A Flask web application where students take a 20-question skills assessment 
and receive instant performance feedback with category-level recommendations.

## 🛠️ Tools & Methods
`Python` `Flask` `Scikit-learn` `Random Forest` `SVM` `KNN` `Decision Tree` `Pandas` `Joblib`

## 📁 Project Files
| File | Purpose |
|---|---|
| `train.ipynb` | Model training notebook — all 4 algorithms |
| `app.py` | Flask web application |
| `dataset.py` | Dataset generation script |
| `predict.py` | Prediction pipeline |
| `performance_prediction_dataset.csv` | Skills dataset (1,000 records) |
| `student_performance.csv` | Overall performance dataset |
