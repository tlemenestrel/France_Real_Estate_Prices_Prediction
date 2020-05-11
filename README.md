![Image of a tree of the XGBoost model](https://github.com/tlemenestrel/France_Real_Estate_Prices_Prediction/blob/master/Images/drawing.jpg)

# Predicting real estate prices in France using XGBoost 

This project is a Machine Learning model to predict real estate prices of properties across France. It is a supervised regression task. The model used for this project is XGBoost.

## Dataset

The dataset contains the data of more of 350+ properties across France. The features are:

* the city where the property is located (Aix-En-Provence, Vincennes, Toulouse, Paris, Marseille, Manosque, Lyon, Issy-Les-Moulineaux, Gif Sur Yvette, Enghien Les Bains or Bourg La Reine)

* the region (Paca, Ile de France or Sud Ouest)

* the type (F1, F2, F3, F4, F5, F6, F7)

* the area in square metres 

* the rent per year in €  

* the price of the property in €

## Features importance

![Image of features importance](https://github.com/tlemenestrel/France_Real_Estate_Prices_Prediction/blob/master/Images/xgboost_features_importance.png)

For this dataset, the two most dominant features are clearly the annual rent and the area of the property, which is expected for a ML model on real estate prices. The other features help to fine-tune the accuracy of the model.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### How to download a copy of the project


### Libraries to install

* [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
* numpy 
* seaborn 
* matplotlib
* sklearn
* xgboost
* graphviz

## Author

* **Thomas Le Menestrel** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](/master/LICENSE.md) file for details
