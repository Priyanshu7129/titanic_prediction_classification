# Titanic prediction classification

## Overview

This repository contains the code and resources for a Machine Learning project to predict survival on the Titanic using the XGBoost algorithm. The goal of this project is to build a model that can accurately predict whether a passenger survived or not based on various features like age, gender, ticket class, etc.

## Dataset

The dataset used for this project is the famous "Titanic: Machine Learning from Disaster" dataset from Kaggle. It contains information about passengers onboard the Titanic, including whether they survived or not. The dataset is split into a training set and a test set, with the target variable "Survived" missing in the test set. The training set is used to train the XGBoost model, and the test set is used to evaluate the model's performance.

## Dependencies

To run the code in this repository, you will need the following dependencies:

- Python 3.x
- pandas
- numpy
- scikit-learn
- xgboost

You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn xgboost
```



## Usage

1. Ensure you have installed all the dependencies mentioned above.

2. Clone this repository to your local machine:

3. Place the Titanic dataset files (`train.csv` and `test.csv`) inside the current directory.

4. Run the script:

  5. The script will execute the following steps:
   - Data preprocessing: Cleaning, imputation, and feature engineering.
   - Model training: Training the XGBoost model on the preprocessed data.
   - Model evaluation: Evaluating the model's performance on the test set.
   - Saving results: Saving evaluation metrics and model performance in the `results/` directory.

## Results

After running the script, you will find the evaluation metrics and model performance . 
## Conclusion

This project demonstrates how to use XGBoost, a powerful gradient boosting algorithm, for predicting survival on the Titanic dataset. Feel free to explore the code and modify the parameters to further improve the model's performance. Happy coding and may the odds be ever in your favor! 🚢🕵️‍♀️
