# Impacts of Scaling Methods on Logistic Regression Model

This repository explores the effect of different scaling methods on the performance of a logistic regression model applied to a dataset from a social network advertising campaign. The primary objective is to predict whether a user will purchase a product based on their age, estimated salary, and whether or not they made a purchase.

## Dataset

The dataset used in this project is named "Social_Network_Ads.csv." It includes information about users' age, estimated salary, and whether they made a purchase. The dataset is preprocessed to select relevant features for modeling.

## Dependencies

The code utilizes the following libraries:
- pandas
- scikit-learn

Make sure to have these libraries installed in your Python environment to run the code successfully.

## Code Description

- `scaling_approach.ipynb`: This Jupyter Notebook contains Python code implementing logistic regression using different scaling methods: normalization and Min-Max scaling. The notebook demonstrates how each scaling method affects the model's accuracy compared to the previous version, which used standard scaling.
- `Social_Network_Ads.csv`: The dataset used for training and testing the model.
- `README.md`: This file, providing an overview of the project, instructions, and information.

## Usage

1. Clone the repository to your local machine.
2. Ensure you have the required dependencies installed.
3. Open and run the `scaling_approach.ipynb` notebook in a Jupyter environment or any Python IDE.
4. Follow the instructions within the notebook to execute the code and observe the results.

## Results

The code demonstrates how different scaling methods impact the performance of the logistic regression model. It compares the accuracy of the model using normalization and Min-Max scaling against the previous version, which utilized standard scaling. The results reveal any degradation or improvement in accuracy due to the choice of scaling method.

## Previous Repository

A previous version of this project achieved a 90% accuracy rate using standard scaling. However, the updated version explores alternative scaling methods to assess their impact on model performance.
