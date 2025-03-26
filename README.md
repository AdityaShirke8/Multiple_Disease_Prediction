# # Multiple Disease Prediction System

## Overview
The **Multiple Disease Prediction System** is a machine learning-based web application built using **Streamlit**. It predicts the likelihood of an individual having **Diabetes**, **Heart Disease**, or **Parkinson's Disease** based on user-provided input values. The application loads pre-trained models and provides real-time predictions.

## Features
- **Diabetes Prediction** 💉🩺
- **Heart Disease Prediction** 🚨🚑
- **Parkinson's Disease Prediction** 📊🗺️
- User-friendly **Streamlit UI** 🖥️
- Interactive input fields for real-time prediction

## Technologies Used
- **Python** 🐍
- **Streamlit** (for UI) 🖥️
- **Scikit-learn** (for ML models) 🤖
- **Pickle** (for model persistence) 🛠️

## Project Structure
```
Multiple_Disease_Prediction/
│── diabetes.csv              # Diabetes dataset
│── heart.csv                 # Heart disease dataset
│── parkinsons.csv            # Parkinson's dataset
│── Model_Diabetes.ipynb      # Jupyter notebook for diabetes model
│── Model_Heart.ipynb         # Jupyter notebook for heart disease model
│── Model_Parkinson.ipynb     # Jupyter notebook for Parkinson's model
│── diabetes_disease_model.sav  # Trained diabetes model
│── heart_disease_model.sav     # Trained heart disease model
│── parkinsons_disease_model.sav # Trained Parkinson's model
│── models_page.py            # Main Streamlit application
│── README.md                 # Project documentation
```

## Installation & Setup
1. Clone the repository:

2. Install the required dependencies:

3. Run the Streamlit application:
   ```bash
   streamlit run models_page.py
   ```

## How to Use
1. Select the type of disease prediction from the sidebar.
2. Enter the required input parameters.
3. Click on the **Test Result** button.
4. View the prediction result displayed on the screen.

## Model Details
- **Diabetes Prediction Model**: Uses features such as glucose level, BMI, insulin, etc.
- **Heart Disease Prediction Model**: Uses features like age, blood pressure, cholesterol, etc.
- **Parkinson's Disease Prediction Model**: Analyzes vocal parameters to detect Parkinson's symptoms.

## Contributing

---
**Author:** Aditya Shirke



