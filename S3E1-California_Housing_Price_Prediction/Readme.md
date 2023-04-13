# California Housing Price Prediction

This repository contains the Jupyter Notebook and supporting files for the California Housing Price Prediction project. 
The goal of this project is to predict the median house value in California using various machine learning algorithms. 
The dataset used for this project was obtained from a Kaggle competition (https://www.kaggle.com/competitions/playground-series-s3e1/overview).

## Dataset

The dataset for this competition consists of two parts: train and test. Both datasets contain information about the housing prices in California, with features described below. The target variable is the median house value(expressed in hundreds of thousands of dollars, i.e. $100,000), which we will try to predict using various machine learning algorithms. The evaluation metric is going to be the standard Root Mean Squared Error (RMSE)

- MedInc - Median income in block group
- HouseAge - Median house age in block group
- AveRooms - Average number of rooms per household
- AveBedrms - Average number of bedrooms per household
- Population - Block group population
- AveOccup - Average number of household members
- Latitude - Block group latitude
- Longitude - Block group longitude


## Overview

1. Exploratory Data Analysis (EDA)
2. Data Preprocessing
    - Feature Engineering
    - Box-Cox Transformation
    - Feature Scaling
    - Feature Selection
3. Modeling
4. Model Evaluation and Selection
5. Hyperparameter Tuning

## Repository Structure

- `PS - S3E1, California House price prediction.ipynb`: Jupyter Notebook containing the main code for the project.
- `README.md`: This file, containing an overview and description of the project.

## Getting Started

To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Open the `PS - S3E1, California House price prediction.ipynb` notebook using Jupyter Notebook or JupyterLab.
3. Run the cells in the notebook to explore the dataset, preprocess the data, and build the predictive models.

## Dependencies

- Python (>= 3.6)
- NumPy
- pandas
- Matplotlib
- seaborn
- scikit-learn
- scipy


## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/mohitseventeens/Kaggle-Playground_Series/blob/main/LICENSE) file for more details.
