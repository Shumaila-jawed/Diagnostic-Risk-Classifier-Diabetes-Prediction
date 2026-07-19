# Diagnostic_Risk_Classifier

A Machine Learning web application that predicts the **likelihood of Diabetes** in a patient based on biometric health data.

This project demonstrates an end-to-end Machine Learning workflow, including data preprocessing, model training, evaluation, explainability, and deployment using **Streamlit**.

---

## 📌 Project Overview

This project uses a **Random Forest Classifier** to predict whether a patient is at risk of diabetes based on key health biometrics.

The focus of this project is on maximizing **Recall** (minimizing false negatives), since missing an actual diabetic patient is more critical than a false alarm in a medical context.

The application allows users to enter patient details through a simple web interface and receive an instant risk prediction.

---

## 🚀 Features

- Predict Diabetes Risk
- User-friendly Streamlit interface
- Data preprocessing (handling invalid biometric values)
- Random Forest Classifier
- Class balancing for better Recall
- Model Evaluation
- Real-time Prediction

---

## 📂 Dataset Features

The model was trained using the following features:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:

- Outcome (Diabetic / Not Diabetic)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib
- SHAP

---

## 📊 Machine Learning Workflow

1. Data Collection
2. Data Cleaning (handling invalid zero values)
3. Data Preprocessing
4. Train-Test Split
5. Random Forest Model Training (class-balanced)
6. Model Evaluation (Recall-focused)
7. Model Explainability using SHAP
8. Save Trained Model
9. Deploy with Streamlit

---

## 📁 Project Structure

```text
Diagnostic-Risk-Classifier/

│── app.py
│── train_model.py
│── requirements.txt
│── model.pkl
│── feature_names.pkl
│── README.md
```

---

## 🌐 Deployment

This project is deployed using **Streamlit Community Cloud**.

---

**Shumaila Jawed**

Machine Learning | AI | Data Science

LinkedIn:
https://www.linkedin.com/in/shumaila-jawed-87a55a33a?utm_source=share_via&utm_content=profile&utm_medium=member_android

fb:
https://www.facebook.com/share/1E5rpVsRug/

Live Demo: *https://diagnostic-risk-classifier-diabetes-prediction-6nvfjjdsfmcgfkq.streamlit.app/*

---

## 📄 License

This project is for educational and portfolio purposes.
