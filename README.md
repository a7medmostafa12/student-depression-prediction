# 🎓 Student Depression Prediction

A Machine Learning project that predicts whether a student is likely to experience depression based on demographic, academic, and lifestyle-related factors.

This project was developed as part of a Machine Learning course and compares multiple classification algorithms to identify the best-performing model.

---

## 📌 Project Overview

Student mental health has become an increasingly important issue in educational institutions. This project aims to build a predictive model that can help identify students who may be at risk of depression using machine learning techniques.

The project includes:

- Data preprocessing
- Feature encoding
- Feature scaling
- Model training
- Performance evaluation
- Interactive prediction interface using Gradio

---

## 📂 Dataset

**Dataset:** Student Depression Dataset

The dataset contains information such as:

- Age
- Academic Pressure
- Study Satisfaction
- Sleep Duration
- Dietary Habits
- Financial Stress
- Family History of Mental Illness
- Work Pressure
- Job Satisfaction
- Degree
- Profession
- Gender
- City
- CGPA
- And other student-related attributes

Target variable:

- **Depression**
  - 0 → No Depression
  - 1 → Depression

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Handling categorical variables using Label Encoding
- Train/Test Split (80% / 20%)
- Feature Scaling using StandardScaler (for Logistic Regression)

---

## 🤖 Machine Learning Models

Three classification models were implemented and compared:

- Logistic Regression
- Random Forest
- XGBoost

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|---------:|----------:|--------:|---------:|
| Logistic Regression | **84.55%** | **85.91%** | **88.07%** | **86.97%** |
| Random Forest | 83.84% | 85.08% | 87.79% | 86.42% |
| XGBoost | 84.07% | 85.29% | 87.97% | 86.61% |

Based on the evaluation metrics, **Logistic Regression** achieved the best overall performance on this dataset.

---

## 🖥️ Interactive Application

The project includes a Gradio interface that allows users to:

- Enter student information
- Predict depression risk instantly
- Demonstrate the trained model in an easy-to-use web interface

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Gradio

---

## 📁 Repository Structure

```
Student-Depression-Prediction/
│
├── student.ipynb
├── README.md
├── requirements.txt
└── (Dataset if permitted)
```

---

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/your-username/Student-Depression-Prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
student.ipynb
```

Run all cells sequentially.

---

## 📈 Future Improvements

- Hyperparameter tuning
- Explainable AI (SHAP/LIME)
- Continuous model retraining
- Mobile application
- Dashboard for universities
- Early warning system for student counseling

---

## 👥 Team

(Add your team members here)

---

## 📄 License

This project is intended for educational purposes.
