# Boston-house-price web app deployed on Heroku

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
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
The problem that we are going to solve here is that given a set of features that describe a house in Boston, our machine learning model must predict the house price. To train our machine learning model with boston housing data, we will be using scikit-learn’s boston dataset.

In this dataset, each row describes a boston town or suburb. Each row contain a 13 attributes (features) with a target column (price).

Link of the describe house Boston features: [https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names)

  
The deployed web app is live at https://usa-boston-house-price.herokuapp.com/

This web app predict the house price as a function of their input parameters.


The web app was built in Python using the following libraries:
* streamlit
* pandas
* numpy
* scikit-learn
* pickle
