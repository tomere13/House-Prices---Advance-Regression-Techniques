# House Prices - Advanced Regression Techniques

This repository contains a solution for the House Prices - Advanced Regression Techniques competition on Kaggle. The goal of this competition is to use machine learning to create a model that predicts the sales price for each house.

## Dataset

The dataset is provided by Kaggle and includes different kinds of information about the houses such as their overall condition, year built, lot area, neighborhood, and the sale price.

## Solution

The solution uses a GradientBoostingRegressor from sklearn. The code includes preprocessing steps for both numeric and categorical features. The numeric features are imputed and scaled, and the categorical features are imputed and encoded as one-hot vectors.

Hyperparameters of the model are tuned using RandomizedSearchCV. The best model is then used to make predictions on the test set.

## Usage

1. Clone this repository.
2. Download the dataset from the House Prices - Advanced Regression Techniques competition page on Kaggle.
3. Run the Python script to train the model and make predictions.

## Results

The performance of the model can be evaluated by submitting the predictions to Kaggle.

## License

This project is licensed under the MIT License.
