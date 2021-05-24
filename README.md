# Car-Price-Prediction

## Table of Content

* Demo
* Overview
* Technical Aspect
* Installation
* Directory Tree
* Technologies Used

## Demo
Link: <https://vehicle-priceprediction.herokuapp.com/>

![Home](https://user-images.githubusercontent.com/84587490/119268842-ccb1e100-bc05-11eb-8a17-339ed7839b06.JPG)

## Overview

This is a simple car price prediction Flask app trained on Random Forest Regrresor. The trained model  takes seven features describing a car (year, showroom price, driven Kilometers,number of owners the car has previously had, fuel type, seller type and transmission type) as an input and predicts the price of the car.

## Technical Aspect
This project is divided into two part:

   1. Training a deep learning model using Random Forest Regrresor.
   2. Building and hosting a Flask web app on Heroku.

## Installation

The Code is written in Python 3.8. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

## Directory Tree
<pre>
├── data 
│   ├── car dataset.csv 
├── notebooks
│   ├── Car price.ipynb
├── templates
│   ├── index.html
├── Procfile 
├── README.md 
├── RandomForestRegressor.pkl
├── app.py
├── main.py
└── requirements.txt
</pre>
## Technologies Used
![python](https://camo.githubusercontent.com/3cdf9577401a2c7dceac655bbd37fb2f3ee273a457bf1f2169c602fb80ca56f8/68747470733a2f2f666f7274686562616467652e636f6d2f696d616765732f6261646765732f6d6164652d776974682d707974686f6e2e737667)  
[![sklearn](https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png)](https://scikit-learn.org/stable/) [![Gunicorn-logo](https://gunicorn.org/images/logo.jpg)](https://gunicorn.org/)
[![flask](https://user-images.githubusercontent.com/84587490/119322349-9cfaeb80-bc8e-11eb-8b87-c8f7b27e3b2f.png)](https://flask.palletsprojects.com/en/2.0.x/) [![heroku](https://user-images.githubusercontent.com/84587490/119322376-a08e7280-bc8e-11eb-8429-ff308e181cdb.png)](https://www.heroku.com/)




