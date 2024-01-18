# Movie Recommendation System

![movie_recommendation_system](https://github.com/aminahagi/Recommendation-System/assets/117739559/8f1bc681-ce60-4ad7-9943-1d13abf42f7e)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Understanding](#Data-Understanding)
- [Data Preparation](#Data-Preparation)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Content-Based Recommendation](#Content-Based-Recommendation)
- [Collaborative Filtering](#Collaborative-Filtering)
- [Model-Based Recommendation](#model-based-recommendation)
- [Contributing](#contributing)
- [Authors](#Authors)

## Introduction

This Movie Recommendation System is a Python-based project that provides movie recommendations to users based on various recommendation techniques. It combines Data Understanding, Data Preparation, Exploratory Data Analysis(EDA), Content-Based, Collaborative Filtering and Model-Based recommendation approaches to offer personalized movie suggestions.

## Features

- Data Understanding
- Data Preparation
- Exploratory Data Analysis
- Content-Based Recommendation
- Collaborative Filtering
- Model-Based Recommendation
- User-friendly interface
- Easy-to-use API
- Customizable recommendation parameters


## Getting Started

### Prerequisites

To run this project, you need the following prerequisites:

- Python 3.x
- Pandas
- Scikit-learn
- Surprise
- Flask (for the web interface)

You can install these packages using pip:

        pip install pandas scikit-learn scikit-surprise flask

## Installation
Clone this repository:

        git clone https://github.com/your-username/movie-recommendation-system.git

Change to the project directory:

        cd movie-recommendation-system


## Data Understanding
The dataset used in this project contains 100,836 ratings and 3,683 tag applications across 9,742 movies. It includes information about movies, user ratings, and tags. Key data files include:
- `movies.csv`: Contains movie information (movieId, title, genres).
- `ratings.csv`: Contains user ratings (userId, movieId, rating).
- `tags.csv`: Contains user-generated metadata about movies (userId, movieId, tag).
- `links.csv`: Provides identifiers for linking to external movie-related sources (imdbId, tmdbId).

## Data Preparation
- Irrelevant columns, such as `timestamp`, were removed from the dataset.
- Missing values were checked and handled (if any).
- Duplicate values were checked and removed (if any).

## Exploratory Data Analysis
- Explored different movie genres and their counts.
- Visualized the top 5 movie genres and their percentage ratios.
- Analyzed top-watched movies.
- Analyzed top-rated movies.
- Visualized the rating distribution.

## Content-Based Recommendation
Our content-based recommendation system uses movie genres and user preferences to suggest similar movies. It calculates the TF-IDF (Term Frequency-Inverse Document Frequency) matrix and uses the sigmoid kernel for similarity scores.

## Collaborative Filtering
The collaborative filtering technique provides movie recommendations based on user-user similarity. It uses a user-item matrix and computes the similarity between users. You can choose between user-based and item-based collaborative filtering.

## Model-Based Recommendation
Our model-based recommendation uses matrix factorization and the SVD algorithm to predict movie ratings for users. It fine-tunes the model parameters for optimal performance.

## Contributing
We welcome contributions from the community. If you'd like to contribute to this project, please follow these steps:

### Fork the repository.
1. Create a new branch for your feature:

        git checkout -b feature-name.
   
2. Make your changes and commit them:
 
       git commit -m 'Add feature-name'.
3. Push to the branch:
  
       git push origin feature-name.
   
4. Create a pull request.

## Authors
- [Joy Ogutu](https://github.com/Ogutu01)
- [David Ambani](https://github.com/bulemi2)
- [Brian Chacha](https://github.com/MarwaBrian)
- [Dennis Kimani](https://github.com/dennismathu)
- [Amina Hagi](https://github.com/aminahagi)
- [Sadi Kiri](https://github.com/Gsothr1234)
