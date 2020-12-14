# Boston-house-price web app deployed on Heroku

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Run the Web App on the local machine](#run-the-Web-app-on-the-local-machine)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#technologies-used)
  
## Demo
Link: [https://usa-boston-house-price.herokuapp.com/](https://usa-boston-house-price.herokuapp.com/)

[![](https://raw.githubusercontent.com/kh-bilal/Dataset/master/demo_Image.png)](https://usa-boston-house-price.herokuapp.com/)

## Overview
The problem that we are going to solve here is that given a set of features that describe a house in Boston, our machine learning model must predict the house price. 

To train the machine learning model, we used the scikit-learn’s boston dataset. In this dataset, each row describes a boston town or suburb. Each row contain a 13 attributes (features) with a target column (price).

Link of the describe house Boston features: [https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/housing.names)

## Technical Aspect
This project is divided into four parts:
1. [House Prices: Comprehnsive data exploration, Evaluation and Comparison between several machine learning models.](https://github.com/kh-bilal/Data-Science-Portfolio/blob/main/Prediction_Boston_Housing_Prices/boston-house-price-prediction.ipynb)
2. [Create pickle file for the best obtained ML model.](https://github.com/kh-bilal/Data-Science-Portfolio/blob/main/Prediction_Boston_Housing_Prices/Create_pkl_model.ipynb)
3. [Building a Streamlite web app.](https://github.com/kh-bilal/Data-Science-Portfolio/blob/main/Prediction_Boston_Housing_Prices/Streamlit-Boston-app.py)
4. Hosting a Streamlit web app on Heroku.

## Installation
The Code is written in Python 3.8.5. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
## Run the Web App on the local machine
Run this command in your terminal 
```bash
streamlit run Streamlit-Boston-app.py
```
## Deployement on Heroku
Follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/kh-bilal/Data-Science-Portfolio/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/kh-bilal/Data-Science-Portfolio/issues/new). Please include sample queries and their corresponding results.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://www.analyticsvidhya.com/wp-content/uploads/2015/01/scikit-learn-logo.png" width=280>](https://www.analyticsvidhya.com/wp-content/uploads/2015/01/scikit-learn-logo.png) [<img target="_blank" src="https://static.javatpoint.com/tutorial/pandas/images/python-pandas.png" width=200>](https://static.javatpoint.com/tutorial/pandas/images/python-pandas.png) [<img target="_blank" src="https://miro.medium.com/max/765/1*cyXCE-JcBelTyrK-58w6_Q.png" width=280>](https://miro.medium.com/max/765/1*cyXCE-JcBelTyrK-58w6_Q.png) [<img target="_blank" src="https://assets.website-files.com/5dc3b47ddc6c0c2a1af74ad0/5e18182ad27bcfbb9dff263a_RGB_Logo_Horizontal_Color_Light_Bg.png" width=200>](https://assets.website-files.com/5dc3b47ddc6c0c2a1af74ad0/5e18182ad27bcfbb9dff263a_RGB_Logo_Horizontal_Color_Light_Bg.png)

[<img target="_blank" src="https://logos-download.com/wp-content/uploads/2016/09/Heroku_logo.png" width=280>](https://logos-download.com/wp-content/uploads/2016/09/Heroku_logo.png)
