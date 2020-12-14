# Boston-house-price web app deployed on Heroku

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run](#run)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [To Do](#to-do)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  * [Team](#team)
  * [License](#license)
  * [Credits](#credits)
  
## Demo
Link: [https://usa-boston-house-price.herokuapp.com/](https://usa-boston-house-price.herokuapp.com/)

[![](https://raw.githubusercontent.com/kh-bilal/Dataset/master/demo_Image.png)](https://usa-boston-house-price.herokuapp.com/)

## Overview
The problem that we are going to solve here is that given a set of features that describe a house in Boston, our machine learning model must predict the house price. 

To train the machine learning model, we used the scikit-learn’s boston dataset. In this dataset, each row describes a boston town or suburb. Each row contain a 13 attributes (features) with a target column (price).

Link of the describe house Boston features: [https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names)

## Technical Aspect
This project is divided into two part:
1. [House Prices: Comprehnsive data exploration, Evaluation and Comparison between several machine learning models.](https://github.com/kh-bilal/Data-Science-Portfolio/blob/main/Prediction_Boston_Housing_Prices/boston-house-price-prediction.ipynb)
2. [Create pickle file for the best obtained ML model](https://github.com/kh-bilal/Data-Science-Portfolio/blob/main/Prediction_Boston_Housing_Prices/Create_pkl_model.ipynb)
2. Building and hosting a Streamlite web app on Heroku.
    - A user can choose image from a device or capture it using a pre-built camera.
    - Used __Amazon S3 Bucket__ to store the uploaded image and predictions.
    - Used __CSRF Token__ to protect against CSRF attacks.
    - Used __Sentry__ to catch the exception on the back-end.
    - After uploading the image, the predictions are displayed on a __Bar Chart__.
  
The deployed web app is live at https://usa-boston-house-price.herokuapp.com/

This web app predict the house price as a function of their input parameters.


The web app was built in Python using the following libraries:
* streamlit
* pandas
* numpy
* scikit-learn
* pickle
