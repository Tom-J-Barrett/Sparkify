# Sparkify

As part of final project for my Udacity Data Science Nanodegree a Spark project to predict churn on a Spotify inspired dataset was undertaken.

## Dataset
The Sparkify dataset is used to mimic the type of data you may find for a music streaming app. Think a subset of Spotify user records. Millions of user stream data through the app daily either on the add ridden free version or the paid service. Users can downgrade or upgrade their subscription tier at any time, so their satisfaction with the service is very important. This dataset is used to try and predict if users will downgrade or upgrade their accounts.

## Blog Post
A blog [post](https://medium.com/@tom.barrett1997/sparkify-an-introduction-to-spark-in-python-6e5789f77263) has been written on medium for this repo.

## Notebook
The notebook in this repo consists of data exploration, feature engineering and modelling required to write the blog post.

## Results
A Random Forest Classifier was trained using the subset of data provided in IBM Watson Studio. Using a cross validator, an accuracy of 90.9% and a F1 score of 0.897 was recorded.
