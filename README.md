Multiple Disease Prediction using Machine Learning

This project aims to predict the likelihood of three major diseases: Heart Disease, Diabetes, and Parkinson’s Disease using machine learning algorithms (Logistic Regression and Support Vector Machine). The project is developed using Streamlit to create an interactive web interface for real-time predictions.

Project Overview

The model is trained using datasets available on Kaggle, and it leverages machine learning models to predict the presence of these diseases based on user input data. The application is built using Streamlit, which allows easy interaction for disease prediction. The models have been trained and then deployed on Heroku for online access.

Features
Heart Disease Prediction: Predicts the likelihood of heart disease based on various medical features like age, cholesterol levels, blood pressure, etc.
Diabetes Prediction: Predicts the possibility of diabetes based on factors such as age, BMI, glucose level, etc.
Parkinson’s Disease Prediction: Predicts the chances of Parkinson’s disease based on features like motor activity data.
Technologies Used
Python: Programming language used for the project.
Streamlit: Framework for building the interactive web interface.
Scikit-learn: Machine learning library used for implementing the prediction models.
Pandas: Used for data manipulation and analysis.
NumPy: Used for reshaping input data into arrays.
Pickle: Used to save the trained machine learning models.
Heroku: Platform used to deploy the app for real-time prediction.
Installation Instructions
To run this project on your local machine, follow these steps:

Prerequisites
Python 3.x or above
Required Libraries:
Pandas
NumPy
Streamlit
Scikit-learn
Pickle
Step-by-step Setup
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/multiple-disease-prediction.git
cd multiple-disease-prediction
Install required dependencies: You can use pip to install the necessary libraries:

bash
Copy code
pip install -r requirements.txt
Or you can manually install the required libraries:

bash
Copy code
pip install pandas numpy scikit-learn streamlit pickle
Run the Streamlit App: To run the application, open the terminal and run:

bash
Copy code
streamlit run app.py
The application will open in your browser, where you can input data to predict the diseases.

Model Training and Prediction
The project uses two machine learning models:

Logistic Regression: Used for binary classification, determining the presence of a disease (yes/no).
Support Vector Machine (SVM): Another classification model used for more complex data patterns.
Both models are trained using datasets from Kaggle and are serialized using Pickle for easy reuse in the Streamlit web app.




