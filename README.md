# ML-Capstone-Prediction-Projects

Overview
This repository contains four machine learning capstone projects focusing on predictive modeling in different domains: airline pricing, heart disease detection, insurance cost estimation, and house price prediction.
Each project involves data preprocessing, model building, evaluation, and interpretation to achieve high accuracy and reliability.

Projects
1. Flight Price Prediction (Accuracy: 85%)
Predicts airline ticket prices based on factors such as airline, source, destination, departure time, duration, and number of stops.
Useful for travelers and companies for better planning and pricing.

2. Heart Disease Prediction (Accuracy: 80%)
Predicts the presence of heart disease in individuals based on various medical attributes such as blood pressure, cholesterol, and maximum heart rate achieved.
Assists healthcare professionals in early detection and treatment planning.

3. Insurance Cost Prediction (Accuracy: 90%)
Predicts the medical insurance charges for individuals based on their age, gender, BMI, number of children, smoking status, and region.
Supports both insurers and customers in understanding and planning medical costs.

4. House Price Prediction (Accuracy: 90%)
Predicts housing prices based on features like area, number of bedrooms and bathrooms, location, and furnishing status.
Helps buyers, sellers, and real estate investors make informed decisions.

Common Challenges Faced
Presence of null values and missing data

Detection and treatment of outliers

Handling of categorical features (e.g., airline names, regions, chest pain types)

Data imbalance in classification problems (especially in Heart Disease Prediction)

Feature scaling for certain algorithms

Ensuring the model generalizes well and does not overfit

Tools and Technologies Used
Programming Language: Python

Libraries:

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Environment: Jupyter Notebook

Algorithms Used
Regression Models:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Classification Models:

Logistic Regression

Random Forest Classifier

Folder Structure
Copy
Edit
ML-Capstone-Prediction-Projects/
│
├── Flight_Price_Prediction/
│   ├── flight_price_prediction.ipynb
│   └── README.md
│
├── Heart_Disease_Prediction/
│   ├── heart_disease_prediction.ipynb
│   └── README.md
│
├── Insurance_Cost_Prediction/
│   ├── insurance_cost_prediction.ipynb
│   └── README.md
│
├── House_Price_Prediction/
│   ├── house_price_prediction.ipynb
│   └── README.md
│
└── README.md (This common file)
How to Run
Clone the repository.

Install required libraries:

nginx
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Open each project's Jupyter Notebook (.ipynb file).

Execute the cells step-by-step to view the full workflow: from data analysis to model building and prediction.

Future Enhancements
Hyperparameter tuning using GridSearchCV or RandomizedSearchCV

Model deployment using Flask or Streamlit

Adding dashboards and visualizations for better interpretation

Deployment on cloud platforms like AWS/GCP

Thank you for checking out my projects! Feel free to explore each folder for detailed notebooks and explanations.

