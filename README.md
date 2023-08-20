
# Passive Aggressive Regressor for House Rent Prediction

This repository contains code for implementing a Passive Aggressive Regressor model to predict house rent prices using machine learning. The project demonstrates the process of data preprocessing, model training, hyperparameter tuning, cross-validation, and model evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Cross-Validation](#cross-validation)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to predict house rent prices using the Passive Aggressive Regressor model. This machine learning model is trained on features such as 'Likes', 'Saves', 'Comments', 'Shares', 'Profile Visits', and 'Follows' to predict the 'Impressions' (rental prices).

## Prerequisites

##### clone the repository : 

```bash
git clone https://github.com/Mohshaikh23/Instagram-Reach-Analysis.git
```

Before running the code, ensure you have the required libraries installed:

- numpy
- pandas
- scikit-learn

You can install them using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Usage

1. Load your dataset into the 'data' DataFrame in the code.
2. Run the code in a Python environment.

## Hyperparameter Tuning

Hyperparameter tuning is performed using GridSearchCV to find the best combination of hyperparameters for the Passive Aggressive Regressor. The parameters tuned include 'C' (regularization parameter), 'fit_intercept', and 'max_iter'.

## Cross-Validation

Cross-validation is conducted to assess the model's performance using multiple subsets of the training data. The cross-validation scores provide an indication of how well the model generalizes to new data.

## Model Evaluation

The model's performance is evaluated on a held-out test dataset. Metrics such as Mean Squared Error (MSE) and R-squared score are calculated to assess how well the model's predictions align with the actual values.

## Results

The best model obtained from hyperparameter tuning is presented along with its performance metrics, including cross-validation scores, mean CV score, MSE, and R-squared score.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.