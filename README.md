Stress Detection System using Decision Tree
Overview

The Stress Detection System is a machine learning application that predicts whether a person is experiencing stress based on input features. The project uses a Decision Tree Classifier trained on a stress dataset and provides predictions through an interactive Streamlit web application. The goal is to make stress prediction simple, fast, and accessible through a user-friendly interface.

Features
Predicts stress levels using a Decision Tree machine learning model.
Interactive web interface developed with Streamlit.
Simple and easy-to-use input form.
Instant prediction results.
Lightweight and efficient application.
Technologies Used
Python
Streamlit
Scikit-learn
Pandas
NumPy
Pickle
Project Structure
app.py – Streamlit application for user interaction.
decisiontree.py – Script used to train the Decision Tree model.
stress.csv – Dataset used for training the model.
stress_model.pkl – Saved trained machine learning model.
requirements.txt – List of required Python libraries.
README.md – Project documentation.
How It Works
The user opens the Streamlit application.
The user enters the required input values.
The application sends the data to the trained Decision Tree model.
The model analyzes the inputs and predicts the stress level.
The prediction is displayed instantly on the screen.
