# Airfare Prediction

This project aims to predict the price of airplane tickets based on various input variables such as date, day, locations, etc , Building best predictor model with Airline data  analysis & prediction future prices of flight tickets.(Client : Airlines – Indigo /Vistara) 

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Tools and Technologies](#tools-and-technologies)
- [Dataset](#dataset)
- [Installation and Running](#installation-and-running)
- [Contributing](#contributing)

## Description

The airfare prediction project uses machine learning algorithms to predict the price of airplane tickets. By inputting variables like date, day, locations, etc., the model will provide an estimated price for the travel.

## Features

- Takes input variables such as date, day, locations, and other relevant features.
- Predicts the price of airplane travel based on these inputs.

## Tools and Technologies

This project utilizes various regression algorithms and selects the best-performing model for predictions. The algorithms tested include:

- Artificial Neural Network (ANN)
- Bayesian Regression
- Decision Tree Regression
- Elastic Net
- Lasso Regression
- Linear Regression
- Quantile Regression
- Random Forest Regression
- Ridge Regression
- K-Nearest Neighbors (KNN) Regression

Among these, the Decision Tree Regression algorithm was found to be the best for this project.

Other technologies used:

- Pickle for model serialization.
- Flask for creating the web application.

## Dataset

The project uses a custom dataset named `vistara.csv`.

## Installation and Running

To run the project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/PavanY02/Airfare.git
    ```
2. Navigate into the directory:
    ```bash
    cd Airfare.git
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python app.py
    ```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.




