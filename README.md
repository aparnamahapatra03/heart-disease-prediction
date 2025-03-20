💓 Heart Disease Prediction System using Machine Learning & Gradio
📌 Overview
This project is a Heart Disease Prediction System built using Machine Learning and a user-friendly Gradio interface. The model predicts whether a patient has a high risk of heart disease based on medical parameters like age, cholesterol levels, chest pain type, and more.

🎯 Features
✅ User-Friendly Interface: Built with Gradio for an interactive experience.
✅ Real-Time Predictions: Provides instant heart disease risk assessment.
✅ Explainable AI: Displays risk factors based on medical indicators.
✅ Fully Documented Inputs: Each medical term is explained in detail.

🛠️ Technologies Used
Python
Gradio (for GUI)
Scikit-Learn (Machine Learning Model)
NumPy & Pandas (Data Processing)
Pickle (Model Serialization)
📊 Input Parameters & Their Meaning
Parameter	Description	Range
Age	Patient’s age	20-100 years
Sex	Male (1) or Female (0)	0 or 1
Chest Pain Type (CP)	0: No pain, 1: Mild, 2: Moderate, 3: Severe	0-3
Resting Blood Pressure (Trestbps)	Normal range: 90-140 mmHg	90-200 mmHg
Cholesterol Level (Chol)	Normal is below 200 mg/dl	100-600 mg/dl
Fasting Blood Sugar (FBS)	>120 mg/dl is concerning	0 or 1
Resting ECG (Restecg)	0: Normal, 1: ST-T abnormality, 2: Ventricular hypertrophy	0-2
Max Heart Rate Achieved (Thalach)	Healthy: 140-170 bpm	60-220 bpm
Exercise-Induced Angina (Exang)	Pain during exercise (Yes = 1, No = 0)	0 or 1
ST Depression (Oldpeak)	Higher values = higher risk	0.0-6.0
ST Slope	0: Downsloping, 1: Flat, 2: Upsloping	0-2
Number of Major Vessels (CA)	0: No blockage, 1-4: Higher blockage risk	0-4
Thalassemia (Thal)	0: Normal, 1: Fixed defect, 2: Reversible defect, 3: Severe issue	0-3


🔬 Machine Learning Model Details
Algorithm Used: Logistic Regression (or specify the model)
Training Dataset: UCI Heart Disease Dataset
Accuracy: 84%


🛡️ Disclaimer
💡 This system is for educational purposes only. It is not a substitute for professional medical diagnosis. Always consult a certified doctor for health concerns.

📌 Contribution & Issues
💡 Want to improve this project? Feel free to fork the repo and create a pull request!
❓ Found a bug? Open an issue here.

🌟 Credits & Acknowledgments
Dataset: UCI Machine Learning Repository
Libraries Used: Gradio, NumPy, Pandas, Scikit-Learn
