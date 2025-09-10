# student-score-predictor
Predicting student exam scores using study hours and attendance with machine learning. This project features data cleaning, visualization, linear regression modeling, and easy-to-use prediction tools—ideal for showcasing data science in education.

## Table of Contents

(a) Project Overview

(b) Features & Visuals

(c) Dataset

(d) Project Structure

(e) Requirements

(f) How to Run


### (A) Project Overview

-> This project demonstrates how data analytics and linear regression can be applied to predict a student's final exam score based on their study habits, specifically hours spent studying and attendance percentage. The aim is to provide educators and students with actionable insights to improve academic performance and enable early intervention.

### (B) Features & Visuals
-> Data cleaning and preprocessing with Pandas and NumPy

-> EDA with correlation matrices, scatter plots, and box plots

-> Model building using linear regression (scikit-learn)

-> Performance evaluation using R² Score and Mean Absolute Error

-> Visualizations for actual vs predicted scores

-> Prediction function for new input data


### (c) Dataset
-> Downloaded from Kaggle: Student Performance Prediction Dataset

### (d) Key features:
-> Hours_Studied

-> Attendance

-> Final_Score

### (e) Project Structure
 
 ├── data/ 
 
 │   └── Student_Performance.csv
 
 ├── notebooks/
 
 │   └── analysis.ipynb 
 
 ├── src/
 
 │   ├── data_processing.py
 
 │   ├── model.py
 
 │   └── predict.py
 
 ├── results/
 
 │   ├── eda_plots.png
 
 │   └── predictions_sample.csv
 
 ├── requirements.txt
 
 └── README.md



### (f) Requirements
-> Install the required libraries:

    bash
    
    pip install pandas numpy matplotlib seaborn scikit-learn joblib

   or 
   
   If fetching data from Kaggle, also:
   
    bash
    
    pip install kaggle


### (g) How to Run
-> Clone this repository:

    git clone https://github.com/your-username/student-score-prediction.git
    
  Download the dataset from Kaggle or use the provided CSV in data/.
  
   Installing dependencies:
   
     pip install -r requirements.txt
     
   Running the analysis notebook or Python scripts:
   

### (h) Predicting a score:

-> Use the function in src/predict.py to enter new values for study hours and attendance.








