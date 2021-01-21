# Car_Price_Prediction
<!-- TABLE OF CONTENTS -->
## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Steps involved](#steps-involved)
  - [Tools used](#tools-used)
  - [Libraries](#libraries)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Data Analysis and Model Selection](#data-analysis-and-model-selection)
  - [Application Development](#application-development)
  - [Model Deployment](#model-deployment)
- [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center">
    <a href="https://carprizpred.herokuapp.com">
        <img src="https://raw.githubusercontent.com/sarvamitra/Car_Price_Prediction/main/prj_home.png.PNG" height="35%" width="50%">
    </a>
</p>
This project uses <a href="https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho?select=car+data.csv">vehicle dataset</a> from cardekho to predict car price.
Dataset contains information about used cars listed on www.cardekho.com.

### Steps involved
* Reading data from source and performing EDA
* Performing feature engineering to feed desired data into ML model
* Finding best set of hyper-parameters using Randomized Search CV to train the model
* Evaluating various Regressor ML models using cross-validation and residual plot
* Creating web application using flask to predict car price based on various attributes.
* Finally, deploying the web application on cloud based platform (i.e. Heroku) 

### Tools used
Following are the tools/frameworks used in developing the application:
* [Python](https://www.python.org/)
* [Flask](https://palletsprojects.com/p/flask/)
* [HTML](https://en.wikipedia.org/wiki/HTML)
* [Heroku](https://www.heroku.com/)
  
### Libraries
Below is the list of python libraries used in this project:
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import os
import sklearn
import flask
```
## Getting Started

### Installation

To install any of the aforementioned libraries, below command can be written in the Anaconda prompt or terminal :

```
pip install <package_name>
```


### Application Development

After model selection, the web application is developed using `flask` which is a python based web-framework. For source code refer `app.py`.

Below are few snapshots of application in use:
* Step 1 Filling attributes related to car
  <p align="center">
    <img src="https://raw.githubusercontent.com//Car_Price_Prediction/master/images/step_1.PNG" height="300px">
  </p>
* Step 2 Displaying predicted cost 
  <p align="center">
    <img src="https://raw.githubusercontent.com//Car_Price_Prediction/master/images/step_2.PNG" height="100px">
  </p>

### Model Deployment

Model is deployed on `heroku` which is a cloud based PaaS. 

Application link : https://carpricesprediction757.herokuapp.com/

## Contact

Sarvamitra A - [LinkedIn](https://in.linkedin.com/in/sarvamitraa)

Project Link: [https://github.com/sarvamitra/Car_Price_Prediction](https://github.com/sarvamitra/Car_Price_Prediction)

