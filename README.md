# Recommender-system-for-books using Machine Learning.
This Project is for online book recommender for all the readers based upon their choices.

## source:
The dataset was obtained from kaggle website.

## Libraries used :
Pandas, Numpy, Scikit Learn, Python 3.9, scipy.

## EDA :
Based upon the data set that obtained from the source, I did some statistical approaches to make my data easy to pipeline into model.
Removed all the unwanted features and added few features into one and made into Pivot table.
Now we used compressed Sparse column farmatting from scipy using the module csc from Scipy.

## Modelling:
Here, I used KNN clustering algorithm for machine learning model and then I gave K as the number of Suggestions of book I needed.

## Pipelining:
Now I imported this model by saving into pickle format and used Streamlit to create APK for this Application and Deployed into Heroku Cloud.


