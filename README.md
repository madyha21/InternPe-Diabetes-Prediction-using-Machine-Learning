# InternPe-Diabetes-Prediction-using-Machine-Learning
## Overview
This project aims to build a Machine Learning model that predicts whether a person is diabetic or not based on medical diagnostic data. It focuses on implementing Support Vector Machine (SVM) for classification tasks.  The model uses a dataset (diabetes.csv) containing several health-related attributes such as Glucose Level, Blood pressure etc. 
## Installation 
1. Clone the repository

   git clone <your-repository-link>
   cd diabetes-prediction-ml

2. Create a virtual environment
   (optional but recommended)

   python -m venv venv
   source venv/bin/activate  # On
   Windows: venv\Scripts\activate

3. Install required dependencies

   pip install -r requirements.txt

4. Dataset
   Ensure that diabetes.csv is present
   in the project directory. You can       download it from kaggle. 

## Usage
1. Run the project

   python diabetes_prediction.py

2. Predicting diabetes

   Modify the input_data tuple with        your own health parameters:

   input_data = (Pregnancies, Glucose,     BloodPressure, SkinThickness,           Insulin, BMI,                           DiabetesPedigreeFunction, Age)

Run the script to get the prediction:

   0 → Not Diabetic
   1 → Diabetic

## Project Structure

diabetes-prediction-ml/
│
├── diabetes_prediction.py   # Main Python script for training and prediction
├── diabetes.csv             # Dataset used for training the model
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation

## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Author
Madiha Manzoor





