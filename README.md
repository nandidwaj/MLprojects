# 🎓 Student Performance Predictor (ML Web App)

## 📌 Overview
The Student Performance Predictor is an end-to-end machine learning web application that predicts a student’s academic performance based on demographic and academic input features.

This project demonstrates:
  - Full ML pipeline development  
  - Model training & evaluation  
  - Web deployment using Flask
    
## 🚀 Features
  - Data preprocessing & feature engineering  
  - Multiple regression models evaluated  
  - Final model: Linear Regression with hyperparameter tuning  
  - Interactive web interface (Flask)  
  - Real-time predictions  
  - Deployed on AWS Elastic Beanstalk  
  - Automated deployment via CI/CD pipeline  

## 🧠 Machine Learning Workflow

### 1. Data Collection
Dataset includes student attributes such as gender, race/ethnicity, parental education, lunch type, test preparation course, reading & writing scores.

### 2. Exploratory Data Analysis (EDA)
  - Identified feature relationships  
  - Checked distributions and correlations  

### 3. Data Preprocessing
  - Encoding categorical variables  
  - Feature scaling  
  - Pipeline creation  

### 4. Model Training
Models evaluated:
  - Linear Regression  
  - Ridge  
  - Lasso  
  - Decision Tree  
  - Random Forest  
  - CatBoost  

### 5. Model Selection
Best model: Linear Regression with hyperparameter tuning  

### 6. Model Saving
Artifacts stored in:
artifacts/
- model.pkl  
- preprocessor.pkl  

## 🗂️ Project Structure
PROJECT/
- artifacts/
- notebook/
- src/
- templates/
- static/
- application.py
- requirements.txt
- setup.py

## ⚙️ Installation & Setup
git clone <your-repo-link>
cd student-performance-predictor
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt

## ▶️ Run the Application
python application.py
Open: http://localhost:5000

## ☁️ Deployment
Deployed using AWS Elastic Beanstalk with CI/CD pipeline.

## 📊 Input Features
- Gender  
- Race/Ethnicity  
- Parental education  
- Lunch  
- Test preparation  
- Reading score  
- Writing score  

## 📈 Output
Predicted Math Score

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- CatBoost  
- Flask  
- HTML, CSS  
- AWS  

## 🔮 Future Enhancements
- Advanced models  
- Better UI  
- Docker deployment  
