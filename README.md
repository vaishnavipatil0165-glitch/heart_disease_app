Heart Disease Prediction Application

A Machine Learning web application that predicts the risk of heart disease based on a user's health and clinical information. The application uses the K-Nearest Neighbors (KNN) algorithm and provides an interactive interface built with Streamlit.

📌 Project Overview

Heart disease is one of the major health concerns worldwide. Early identification of risk factors can help support better health awareness and decision-making.

This project uses a trained Machine Learning model to analyze patient-related information such as age, blood pressure, cholesterol, chest pain type, maximum heart rate, and other clinical parameters.

The trained model is integrated into a Streamlit web application, where users can enter their details and receive a prediction.

🎯 Objectives
Build a Heart Disease Prediction Machine Learning model.
Use the KNN (K-Nearest Neighbors) algorithm for prediction.
Preprocess and scale input data.
Create an interactive web interface using Streamlit.
Allow users to enter patient health information.
Display the predicted heart disease risk.

🖥️ Application Features
👤 Age selection
🚻 Gender selection
❤️ Chest pain type
🩺 Resting blood pressure
🧪 Cholesterol level
🍬 Fasting blood sugar
📊 Resting ECG
💓 Maximum heart rate
🏃 Exercise-induced angina
📉 Oldpeak (ST depression)
📈 ST slope
🔮 One-click prediction
✅ Low-risk result
⚠️ High-risk result

🛠️ Technologies Used
Technology	Purpose
Python	Programming language
Pandas	Data processing
NumPy	Numerical operations
Scikit-learn	Machine Learning
KNN	Classification algorithm
Joblib	Saving and loading ML models
Streamlit	Web application
Jupyter Notebook / Kaggle	Model development

🔮 Prediction Output

The application provides two possible outputs:

✅ Low Risk

The model predicts that the provided input falls into the low-risk class.

⚠️ High Risk

The model predicts that the provided input falls into the high-risk class.

The prediction is based on the trained Machine Learning model and should not be considered a medical diagnosis.
