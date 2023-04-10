# Predictive Maintenance Classification Project 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

<img src="https://www.getmaintainx.com/static/e44a87ec2674c6fdb362cb03302b3e2f/1f9ea/AdobeStock_415433281.webp" />


This project aims to develop a machine failure prediction system using machine learning techniques. The dataset used for this project consists of 10,000 data points stored as rows with 14 features in columns.

Three algorithms, namely logistic regression, decision tree, and random forest, were used for this purpose.

## About the dataset
The dataset contains the following features:

- **UID**: A unique identifier ranging from 1 to 10,000.
- **productID**: Composed of a letter L, M, or H, representing the product quality variants as low (50% of all products), medium (30%), and high (20%) respectively, followed by a variant-specific serial number.
- **air temperature [K]**: Generated using a random walk process and subsequently normalized to a standard deviation of 2 K around 300 K.
- **process temperature [K]**: Generated using a random walk process normalized to a standard deviation of 1 K, added to the air temperature plus 10 K.
- **rotational speed [rpm]**: Calculated from the power of 2860 W, with added normally distributed noise.
- **torque [Nm]**: Torque values normally distributed around 40 Nm, with a standard deviation of 10 Nm and no negative values.
- **tool wear [min]**: H/M/L quality variants add 5/3/2 minutes of wear to the tool used in the process.
- **machine failure**: A label indicating whether the machine failed at this specific data point for any of the listed failure modes.
- **Target**: A binary label indicating whether a machine failure occurred or not.
- **Failure Type**: A multi-class label indicating the type of failure.

The dataset was obtained from Kaggle, and the link can be found [here](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification).

## Installation
Install all libraries requirements by run the following command

> pip install requirements.txt

## Credits

All the credits to [Gabriel Salles do Amaral](https://www.linkedin.com/in/gabriel-salles788/)