# Hypertension Prediction System

A Machine Learning based web application that predicts the stage of hypertension using patient health data and provides clinical recommendations.

This project integrates Machine Learning, Data Analysis, and Web Development to create a cardiovascular risk assessment tool.

------------------------------------------------------------

## Project Overview

Hypertension (high blood pressure) is one of the leading causes of cardiovascular diseases worldwide. Early detection and monitoring can significantly reduce severe health complications such as stroke, heart attack, and kidney disease.

This project analyzes patient health parameters such as:

- Age group
- Gender
- Medical history
- Blood pressure levels
- Symptoms
- Lifestyle factors

Using these inputs, the system predicts the Hypertension Stage and provides clinical recommendations.

------------------------------------------------------------

## Features

Medical Risk Assessment

- Predicts hypertension stage
- Displays prediction confidence percentage
- Provides clinical recommendations
- Color coded risk indicators

Machine Learning Models Tested

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Ridge Classifier
- Naive Bayes

Professional Web Interface

- Clean medical dashboard
- Patient health assessment form
- Real time prediction results
- Responsive layout

------------------------------------------------------------

## Technologies Used

Programming Languages

- Python
- HTML
- CSS

Libraries and Frameworks

- Flask
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Joblib

------------------------------------------------------------

## Project Structure

Hypertension-Prediction
│
├── static
│   └── style.css
│
├── templates
│   └── index.html
│
├── app.py
├── logreg_model.pkl
├── patient_data.csv
├── Data_Collection_&_Preparation.ipynb
├── Exploratory_Data_Analysis.ipynb
└── README.md

------------------------------------------------------------

## Dataset Features

The dataset includes the following attributes.

Gender  
Age Group  
Family History of Hypertension  
Currently Under Medical Care  
Taking Blood Pressure Medication  
Symptom Severity  
Shortness of Breath  
Vision Changes  
Frequent Nose Bleeding  
Time Since Diagnosis  
Systolic Blood Pressure Range  
Diastolic Blood Pressure Range  
Heart Healthy Diet  

Target Variable

Stages

Hypertension Categories

Normal  
Hypertension Stage 1  
Hypertension Stage 2  
Hypertensive Crisis

------------------------------------------------------------

## Machine Learning Workflow

Data Collection
↓
Data Preprocessing
↓
Exploratory Data Analysis
↓
Model Training
↓
Model Evaluation
↓
Model Deployment
↓
Web Application

------------------------------------------------------------

## Model Deployment

The trained model is saved using

joblib.dump(model,"logreg_model.pkl")

The Flask application loads the model using

model = joblib.load("logreg_model.pkl")

Users enter their health parameters through the web interface and receive predictions instantly.

------------------------------------------------------------

## Running the Project

Step 1 Clone the repository

git clone https://github.com/YOUR_USERNAME/hypertension-prediction.git

Step 2 Navigate to project folder

cd hypertension-prediction

Step 3 Install dependencies

pip install -r requirements.txt

Step 4 Run Flask application

python app.py

Step 5 Open browser

http://localhost:5000

------------------------------------------------------------

## Web Application Interface

The application provides

Patient health assessment form  
Hypertension stage prediction  
Risk level indicator  
Clinical recommendations  

------------------------------------------------------------

## Example Prediction Output

Normal Blood Pressure → Low Risk

Stage 1 Hypertension → Moderate Risk

Stage 2 Hypertension → High Risk

Hypertensive Crisis → Emergency

------------------------------------------------------------

## Future Improvements

Integration with wearable health devices  
Real time blood pressure monitoring  
Explainable AI techniques  
Mobile health application  
Larger dataset for improved accuracy  

------------------------------------------------------------

## References

American Heart Association Blood Pressure Guidelines

Scikit-learn Documentation

Research papers on cardiovascular risk prediction

------------------------------------------------------------

## License

This project is licensed under the MIT License.

------------------------------------------------------------
