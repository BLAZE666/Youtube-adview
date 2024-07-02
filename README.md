# YouTube Adview Prediction

This project aims to predict the number of ad views for YouTube videos using various machine learning regression techniques. By analyzing metrics such as views, likes, dislikes, comments, published date, duration, and category, the goal is to build an accurate model for adview prediction.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)

## Introduction
YouTube advertisers pay content creators based on adviews and clicks for the goods and services being marketed. This project aims to estimate the adviews based on other metrics like comments, likes, etc. The objective is to train various regression models and choose the best one to predict the number of adviews.

## Dataset
The dataset includes metrics and other details of about 15,000 YouTube videos. The metrics include:
- `vidid`: Unique Identification ID for each video
- `adview`: The number of adviews for each video (target variable)
- `views`: The number of unique views for each video
- `likes`: The number of likes for each video
- `dislikes`: The number of dislikes for each video
- `comment`: The number of unique comments for each video
- `published`: The date of uploading the video
- `duration`: The duration of the video (in minutes and seconds)
- `category`: Category niche of each video

You can download the dataset from [this link](https://drive.google.com/file/d/1Dv-HF10AUUA03AO_cQvar462eXawk0iQ/view?usp=sharing).


## Requirements
- Python 3.7+
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter
- Keras

