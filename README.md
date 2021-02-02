# Disaster_Tweets_NLP


![picture1]()

*Disaster Photo Source: Author, Unsplash.com*


## Intro
This dataset comes from Kaggle Kernels. This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website. The idea is to create a model using Natural Language Processing to determine if tweets from Twitter can be used to determine a real disaster from just regular tweets.


## README Outline
* Introduction 
* Project Summary
* Repo Contents
* Prerequisites
* Feature and Definitions
* Results
* Future Work
* Built With, Contributors, Authors, Acknowledgments


![picture2]()

*Another picture*


## Repo Contents
This repo contains the following:
* README.md - this is where you are now!
* Disaster_Tweets_Notebook.ipynb - the Jupyter Notebook containing the finalized code for this project.
* LICENSE.md - the required license information.
* sample_submission.csv
* test.csv
* train.csv
* CONTRIBUTING.md 
* Images



## Libraries & Prerequisites
These are the libraries that I used in this project.

* import pandas as pd
* import numpy as np
* import matplotlib.pyplot as plt
* %matplotlib inline
* import seaborn as sns

* from sklearn.model_selection import train_test_split
* from sklearn.preprocessing import StandardScaler

* from sklearn.linear_model import LinearRegression
* from  sklearn.svm import SVR
* from sklearn.tree import DecisionTreeRegressor
* from sklearn.neighbors import KNeighborsRegressor

* import statsmodels.api as sm

* from sklearn.metrics import mean_squared_error
* from sklearn.model_selection import cross_val_score



## Features
These are the features of this dataset.

Columns
* id - a unique identifier for each tweet
* text - the text of the tweet
* location - the location the tweet was sent from (may be blank)
* keyword - a particular keyword from the tweet (may be blank)
* target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)


## Models




## Conclusions





## Future Work



![Picture3]()

*Picture Source: author, freeimages.com*


## Built With:
Jupyter Notebook
Python 3.0
scikit.learn

## Contributing
Please read CONTRIBUTING.md for details

## Authors
Thomas Whipple

## License
Please read LICENSE.md for details

## Acknowledgments
Kaggle - This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here.

