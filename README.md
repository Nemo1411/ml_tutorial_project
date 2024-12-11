# README

## House Price Prediction Model

This repository contains a Jupyter notebook that implements a machine learning model to predict house prices based on various features. The dataset used for training and testing the model includes information about different properties, such as suburb, address, number of rooms, property type, price, and other relevant attributes.

### Table of Contents

- [Installation](#installation)
- [Data](#data)
- [Modeling](#modeling)
- [Results](#results)


### Installation

To run the notebook, you will need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- scikit-learn
- TensorFlow (or Keras)

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

### Data
The dataset used in this project is melb_data.csv, which contains the following columns:

-Suburb
-Address
-Rooms
-Type (house or unit)
-Price
-Method of sale
-Seller
-Date of sale
-Distance from the city
-Postcode
-Number of bedrooms
-Number of bathrooms
-Number of car spaces
-Landsize
-Building area
-Year built
-Council area
-Latitude
-Longitude
-Region name
-Property count


### Modeling
The project utilizes various machine learning models to predict house prices, including:

Linear Regression
Decision Trees
Support Vector Regression (SVR)
Neural Networks
The models are evaluated based on their Mean Absolute Error (MAE) and other relevant metrics.

### Results
The results of the model training and evaluation are visualized using Matplotlib and Seaborn. The performance of each model is compared to determine the best approach for predicting house prices.
