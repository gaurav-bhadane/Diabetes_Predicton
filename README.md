# Diabetes Prediction Using Logistic Regression

This repository contains the code and resources for predicting diabetes using a Logistic Regression model. The project is implemented in Python, utilizing libraries such as pandas, scikit-learn, and Flask for web deployment.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Model Training](#model-training)
4. [Web Application](#web-application)
5. [Setup and Installation](#setup-and-installation)
6. [Usage](#usage)
7. [Results](#results)
8. [Contributing](#contributing)

## Project Overview

The goal of this project is to create a predictive model that can classify whether a person has diabetes based on various medical parameters. The Logistic Regression algorithm is used due to its effectiveness in binary classification problems.

## Dataset

The dataset used for this project is located in the `Dataset` folder. It includes several features such as:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (target variable)

## Model Training

The `Notebooks` folder contains Jupyter notebooks used for data exploration, preprocessing, and model training. Key steps include:
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Scaling
4. Model Training and Evaluation

The trained model is saved in the `Model` folder.

## Web Application

The project includes a Flask web application to allow users to input medical parameters and receive diabetes predictions. The app's files are:
- `app.py`: Main application file
- `templates/index.html`: HTML template for the web interface

## Setup and Installation

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/gaurav-bhadane/Diabetes_Predicton.git
    cd Diabetes_Predicton
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application:
    ```bash
    python app.py
    ```

## Usage

1. Open your web browser and go to `http://127.0.0.1:5000/`.
2. Input the required medical parameters in the form.
3. Click "Predict" to see if the individual is likely to have diabetes.

## Results

The model's performance metrics, such as accuracy, precision, recall, and F1-score, are detailed in the Jupyter notebooks. These metrics help evaluate the effectiveness of the Logistic Regression model in predicting diabetes.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


Feel free to explore the repository and provide feedback or raise issues if you encounter any problems. Happy coding!
