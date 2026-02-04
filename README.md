# MACHINE_LEARNING_PROJECTS_MCA-2026-
Auto MPG Prediction using Linear Regression
📌 Project Overview

This project demonstrates a complete machine learning workflow using the Auto MPG dataset from the UCI Machine Learning Repository. The goal is to predict a car’s fuel efficiency (miles per gallon) based on its weight using a Linear Regression model.

The notebook covers data loading, preprocessing, exploratory data analysis (EDA), model training, and performance evaluation.

📊 Dataset

Source: UCI Machine Learning Repository – Auto MPG Dataset

URL: http://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/auto-mpg.data

Records: 398 vehicles

Features:

mpg (target)

cylinders

displacement

horsepower

weight

acceleration

model_year

origin

car_name

🧹 Data Preprocessing

Loaded the dataset directly from the UCI repository

Assigned meaningful column names

Handled missing values by removing incomplete rows

Selected vehicle weight as the independent variable

Selected MPG as the target variable

🔍 Exploratory Data Analysis (EDA)

Displayed dataset structure and summary statistics

Checked for missing values

Visualized distributions of:

MPG

Vehicle weight

Analyzed average MPG based on:

Number of cylinders

Country of origin

Model year

🤖 Model Building

Algorithm: Linear Regression

Library: scikit-learn

Train-Test Split: 80% training, 20% testing

Trained the model to predict MPG from vehicle weight

Printed model parameters:

Intercept

Regression coefficient (slope)

📈 Model Evaluation

The model was evaluated using:

Mean Squared Error (MSE)

R² Score (Coefficient of Determination)

These metrics help assess prediction accuracy and how well the model explains variance in MPG.

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

scikit-learn

Jupyter Notebook

📁 Project Structure
├── MINI_PROJECT_1.ipynb
└── README.md

🚀 How to Run

Clone the repository

Open the notebook in Jupyter

Run all cells sequentially

Ensure required libraries are installed:

pip install pandas numpy matplotlib scikit-learn

🎯 Key Takeaways

Vehicle weight has a strong inverse relationship with fuel efficiency

Linear Regression provides a simple and effective baseline model

The project demonstrates fundamental ML concepts suitable for beginners

📌 Future Improvements

Use multiple features instead of a single variable

Try advanced models (Polynomial Regression, Random Forest)

Add feature scaling and cross-validation

Improve visualizations

👤 Author

Abhishek Mishra
