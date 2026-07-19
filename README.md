# 🩺 Diagnostic Risk Classifier (Diabetes Prediction)

A machine learning web app that predicts the likelihood of diabetes based on patient biometric data, with a focus on **maximizing Recall** (minimizing false negatives) since missing a sick patient is more dangerous than a false alarm in healthcare.

## 📊 Dataset
Pima Indians Diabetes Dataset — contains biometric data of female patients (age 21+), including glucose level, blood pressure, BMI, insulin, and more, with the target being whether the patient has diabetes.

## 🧠 Model
- **Algorithm:** Random Forest Classifier
- **Class Weight:** Balanced (to reduce false negatives / improve recall)
- **Explainability:** SHAP was used during model development to understand which features (Glucose, BMI, Age) most influence predictions


## 📁 Project Structure

├── app.py               # Streamlit web app
├── train_model.py        # Script to train the model (run in Colab)
├── model.pkl              # Trained Random Forest model
├── feature_names.pkl      # Column order used during training
├── requirements.txt       # Python dependencies
└── README.md





## Developed by Shumaila jawed
Machine Learning Project
