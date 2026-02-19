# ❤️ Heart Disease Prediction System

## 📌 Project Overview
This project is a Machine Learning based web application that predicts the likelihood of heart disease based on clinical parameters such as age, chest pain type, blood pressure, cholesterol level, etc.

The model is trained using supervised learning algorithms and deployed using a Flask web application.

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib / Seaborn
- Flask
- HTML/CSS

---

## 📊 Dataset Information

The dataset contains medical attributes including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate Achieved
- Exercise Induced Angina
- ST Depression
- Target (0 = No Disease, 1 = Disease)

---

## 🧠 Machine Learning Models Used

- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- XGBoost (if used)

The best-performing model was selected based on evaluation metrics like accuracy and confusion matrix.

---

## 🔍 Project Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Model Training & Evaluation
5. Model Saving using Pickle
6. Deployment using Flask Web App

---

## 🌐 How the Web App Works

- User enters health details in the form
- Inputs are passed to the trained ML model
- The model predicts whether the person is at risk of heart disease
- Result is displayed on the screen

---

## 🛠️ How to Run the Project

1. Clone the repository
```
git clone https://github.com/yourusername/heart-disease-prediction.git
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Run the Flask app
```
python app.py
```

4. Open in browser
```
http://127.0.0.1:5000/
```

---

## 📈 Future Improvements

- Add probability score instead of only binary output
- Improve UI design
- Deploy on cloud (AWS/Render/Heroku)
- Add feature importance visualization

---

## 👩‍💻 Author

Shaik Sofiya  
LinkedIn: https://linkedin.com/in/sofiya-shaik175  
GitHub: https://github.com/shaiksofiya17
