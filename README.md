# Diabetes Prediction Web App

This is a web application built using Flask that predicts whether a person has diabetes or not based on health parameters. The project includes data preprocessing, multiple machine learning model training (Decision Tree, Support Vector Classifier, Logistic Regression, and Naive Bayes), hyperparameter tuning, evaluation metrics, and a user-friendly web interface.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The Diabetes Prediction Web App utilizes various machine learning models to predict whether an individual has diabetes based on their health attributes. Users can input their health data, and the app will provide predictions using different trained models.

## Features

- Data Preprocessing: The app handles missing values and outliers in the dataset before training.
- Multiple Machine Learning Models: The app includes Decision Tree Classifier, Support Vector Classifier (SVC), Logistic Regression, and Naive Bayes models.
- Hyperparameter Tuning: Models like Decision Tree and SVC are trained using hyperparameter tuning.
- User-Friendly Interface: Users can easily input their health parameters and receive predictions through a web interface.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python
- Flask
- Required dependencies (specified in `requirements.txt`)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/diabetes-prediction-app.git
cd diabetes-prediction-app
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Place the dataset file diabetes.csv in the appropriate location (/config/workspace/Dataset/).
4. Set up your Flask environment variables or configurations.

## Usage

1. Run the Flask app:
```bash
python app.py
```
2. Access the app in your web browser by navigating to http://localhost:5000.
3. Input your health parameters and submit to get a diabetes prediction.

## Models

The app employs the following machine learning models:

- Decision Tree Classifier: Trained with hyperparameter tuning.
- Support Vector Classifier (SVC): Trained with hyperparameter tuning.
- Logistic Regression: Trained with hyperparameter tuning.
- Naive Bayes Classifier: Trained with default settings.

## Evaluation Metrics

The app provides the following evaluation metrics for the models:

- Accuracy
- Precision
- Recall
- F1-Score

## Contributing

Contributions are welcome! If you have suggestions or improvements, please follow these steps:

1. Fork the repository.
1. Create a new branch: git checkout -b feature/your-feature
1. Commit your changes: git commit -am 'Add a new feature'
1. Push the branch: git push origin feature/your-feature
1. Create a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

If you have questions or need assistance, feel free to contact the project owner at syunus838@gmail.com.

