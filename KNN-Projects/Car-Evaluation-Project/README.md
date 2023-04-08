# Predictive Maintenance Classification Project 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/devsuperior/sds1-wmazoni/blob/master/LICENSE) 

<img src="https://hips.hearstapps.com/hmg-prod/amv-prod-cad-assets/images/17q3/685273/certified-pre-owned-cpo-vehicle-inspections-explained-feature-car-and-driver-photo-686965-s-original.jpg?resize=1200:*" />


The goal of this project is to apply and understand the KNN algorithm, more specifically to test different values for 'k' and to find the best combination between 'k' and f1-score.

## About the dataset
The dataset consists of 1728 data points stored as rows with 7 features in columns. The model evaluates cars according to the following concept structure:

* **buying:** buying price, can be vhigh, high, med, low.
* **maint:** price of the maintenance, can be vhigh, high, med, low.
* **doors:** number of doors, can be 2, 3, 4, 5more.
* **persons:** capacity in terms of persons to carry, can be 2, 4, more.
* **lug_boot:** the size of luggage boot, can be small, med, big.
* **safety:** estimated safety of the car, can be low, med, high.
* **Class:** car rating, can be unacc, acc, good, vgood. 

The dataset was obtained from UCI Machine Learning Repository, and the link can be found [here](https://archive.ics.uci.edu/ml/datasets/car+evaluation).

## Installation
Install all libraries requirements by run the following command

> pip install requirements.txt

## Credits

All the credits to [Gabriel Salles do Amaral](https://www.linkedin.com/in/gabriel-salles788/)
