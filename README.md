# Movie Recommender System

![movie_recommendation_system](https://github.com/aminahagi/Recommendation-System/assets/117739559/8f1bc681-ce60-4ad7-9943-1d13abf42f7e)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Understanding](#data-understanding)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [Authors](#authors)

## Introduction

This Movie Recommendation System is a Python-based project that provides movie recommendations to users based on various recommendation techniques. It combines Data Understanding, Data Preparation, Exploratory Data Analysis(EDA), Content-Based, Collaborative Filtering and Model-Based recommendation approaches to offer personalized movie suggestions.

## Features

- Data Understanding
- Data Preparation
- Exploratory Data Analysis
- Modeling (Recommendation System generation)
- User-friendly interface
- Easy-to-use API



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

## Exploratory Data Analysis
- Explored different movie genres and their counts.
- Visualized the Top 5 movie genres and their percentage ratios.
- Analyzed top-watched movies.
- Analyzed top-rated movies.
- Visualized the rating distribution.

## Modeling
We utilized the following approaches: 
- Content-Based Recommendation
Our content-based recommendation system uses movie genres and user preferences to suggest similar movies. It calculates the TF-IDF (Term Frequency-Inverse Document Frequency) matrix and uses the sigmoid kernel for similarity scores.

- Collaborative Filtering
The collaborative filtering technique provides movie recommendations based on user-user similarity. It uses a user-item matrix and computes the similarity between users. You can choose between user-based and item-based collaborative filtering.

- Model-Based(SVD) Recommendation
Our model-based recommendation uses matrix factorization and the SVD algorithm to predict movie ratings for users. It fine-tunes the model parameters for optimal performance.

## Conclusion
Model-based collaborative filtering techniques offer a powerful and scalable approach to recommendation systems, leveraging advanced algorithms and machine learning models. Their ability to handle sparsity, recognize complex patterns, and scale with growing datasets makes them valuable for large-scale applications.

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

- [David Ambani](https://github.com/bulemi2)


