# Diabetes Prediction Web Application

## Objective
The primary objective of this project is to develop a web application that accurately predicts the likelihood of diabetes based on user-provided health metrics. This tool is designed to help users understand their risk of diabetes and encourage proactive management of their health.

## Overview
This web application predicts the likelihood of diabetes based on user inputs. It leverages a machine learning model that has been fine-tuned using GridSearchCV to optimize performance. The application is built with Python, Streamlit, and Scikit-learn.

## Features
- **User-Friendly Interface:** An intuitive form for entering health data such as age, blood pressure, and glucose levels.
- **Optimized Machine Learning Model:** A pre-trained model fine-tuned using GridSearchCV ensures accurate and reliable predictions.
- **Real-Time Predictions:** Instant feedback on diabetes risk is provided upon form submission.
- **Data Preprocessing:** Includes categorical variable encoding and numerical feature scaling to optimize model performance.

## How It Works
1. **Input Data:** Users input their health information via the web interface.
2. **Data Processing:** The input data is encoded and scaled using pre-trained encoders and a scaler.
3. **Prediction:** The processed data is fed into a pre-trained and optimized machine learning model to predict diabetes likelihood.
4. **Output:** The app displays whether the user is at risk for diabetes or not.

## Technologies Used
- **Python**
- **Streamlit**
- **Scikit-learn**
- **Pandas**
- **Joblib**

## Project Structure
```bash
.
├── deploy.py                # Main application script
├── model.pkl                # Trained and optimized machine learning model
├── requirements.txt         # List of Python dependencies
└── README.md                # Project documentation
