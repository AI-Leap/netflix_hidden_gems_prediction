The link to the medium blog post
https://medium.com/p/622062af6404/edit

# Predict the hidden gem score of a movie on Netflix

![netflix_vft6 jpg](https://user-images.githubusercontent.com/20230956/120425038-868e1780-c393-11eb-856b-6c7499b46d20.png)

The hidden gem score is the highlight of the popularity of a movie.
The higher the hidden gem score, the higher the movie rating. 

## Table of Contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info

### Datasets
Kaggle dataset (Latest Netflix data with 26+ joined attributes) is used for this project.

https://www.kaggle.com/ashishgup/netflix-rotten-tomatoes-metacritic-imdb

This dataset combines data sources from Netflix, Rotten Tomatoes, IMBD, posters, box office information, trailers on YouTube, and more using a variety of APIs.

[Project Background]

Netflix has a lot of quality movies and series with different genres under different categories. People on Netflix have to search through Netflix to know which content is of better quality. That is uneasy and a bit time-consuming. Hidden gem addresses such a problem.
The business idea behind this problem is to know which type of movie can get higher ranting and popularity among viewers.

https://github.com/AI-Leap/netflix_hidden_gems_prediction/blob/main/Netflix_Movie_Prediction.ipynb

In the project, there will be 3 different business understanding for movie industries.

### 1. Which genre of movies or series is the most shown on Netflix from the year 2015 to 2021.

![genre_count](https://user-images.githubusercontent.com/20230956/120663427-03aeaf00-c4b0-11eb-8ae0-ef577350d1ac.png)

### 2. How the movie published trend on Netflix changed.

![movie_count](https://user-images.githubusercontent.com/20230956/120663598-2b9e1280-c4b0-11eb-8152-1d43d2e25168.png)

### 3. The Prediction of Hidden Gem Score

![mae](https://user-images.githubusercontent.com/20230956/120663475-0f9a7100-c4b0-11eb-861f-cc2fd5343d8a.png)

## Technologies
The following libraries are used:
* pandas
* numpy
* collections
* nltk
* matplotlib
* seaborn
* sklearn

## Setup
```
$ pip install jupyter
$ pip install pandas numpy matplotlib seaborn scikit-learn
```
