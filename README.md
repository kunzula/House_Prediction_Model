House Price Prediction Model for Tunisia

This project is a machine learning model developed to predict house prices in Tunisia. It leverages various features such as the size of the property, location, and other relevant factors to predict house sale prices using a linear regression model.

## Project Overview

The goal of this project is to build a model that can accurately predict the sale prices of houses in Tunisia. This will help homeowners, real estate agents, and buyers make more informed decisions when buying or selling properties.

### nstallation
Prerequisites
Make sure you have the following libraries installed:

Python 3.x
- pandas
- numpy
- seaborn
- scikit-learn
- matplotlib
- category_encoders
- ipywidgets

### Features of the Project:
- Data preprocessing (handling missing values, scaling, etc.)
- Feature engineering and selection
- Model training using linear regression
- Evaluation using Root Mean Squared Error (RMSE)
- Visualization of results with prediction lines

## Dataset

The dataset includes various features related to house sales, such as:
- *LotArea*: The size of the property in square meters.
- *SalePrice*: The final sale price of the house.
- Other features (location, number of rooms, etc.)

### Data Preprocessing
- *Scaling*: Both the input features and target variable are scaled using StandardScaler to ensure the model is trained on normalized data.
- *Handling Missing Values*: Missing values are filled with appropriate statistics (mean, median) to ensure data consistency.

## Model Used

A linear regression model is employed to predict house prices. Linear regression was chosen due to its simplicity and interpretability for this problem.

## Evaluation Metrics

The model is evaluated using *Root Mean Squared Error (RMSE)*, which measures the average error between the predicted and actual house prices.

## Results

The model is evaluated using the Mean Squared Error (MSE) and R-squared (R²) metrics. The final visualization shows a scatter plot of the test data points and the corresponding regression line fitted by the model.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/kunzula/House_Prediction_Model.git
    cd house-prices-tunisia

### Usage
You can run the code using the provided Jupyter Notebook file or the Python script:

- Open the Predicting House prices in Tunisia.ipynb file in Jupyter Notebook.
- Run the cells in sequence to preprocess the data, train the model, and visualize the results.
Alternatively, execute the script from the command line if provided.

### License
This project is licensed under the MIT License - see the LICENSE file for details.