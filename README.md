# Recommender Systems

Notebooks and Code for different methods used for recommender systems

#### -- Project Status: [Active]

## Description

This module is designed to go over different techniques used for recommender systems. These techniques will be implement on the MovieLens 100k dataset.

## Methods Implemented

### Content-Based Filtering

Content-Based Filtering is a recommendation system technique that uses the attributes of the items to make recommendations. It works by analyzing the content or features of the items being recommended, and using that information to identify other items that are similar in some way.

For example, if a user has previously liked or interacted with items that have certain characteristics, such as a particular genre of music or a certain type of movie, the system might recommend other items with similar characteristics. 

### Collaborative Filtering

Collaborative filtering is a technique used to make personalized recommendations by identifying patterns in a user's past behavior. In the context of this project, the past behavior we are interested in is the ratings that users have given to movies. By analyzing these ratings, the our model can identify other users who have given similar ratings to the same movies and use their ratings to make recommendations to the user.

#### User-Based

In User-Based Collaborative Filtering, we use the ratings given by similar users to make recommendations for a target user.

#### Item-Based

In Item-Based Collaborative Filtering, we make recommendations that are similar to a target movie. This is done by first obtaining a set of movies that are rated by a particular user and that are most similar to the target. We use this set of movies and the ratings that the user gave to make a prediction on a rating the user would give for the target movie. The premise is that similar movies are rated similarly by the same user.

### Matrix Factorization

#### Singular Value Decomposition (SVD)

SVD works by decomposing the original matrix into three matrices: a matrix of left singular vectors, a diagonal matrix of singular values, and a matrix of right singular vectors. These matrices capture the structure of the original matrix in a way that makes it easier to analyze and manipulate.

The resulting matrices can then be used for various purposes, such as reducing the dimensionality of the original matrix, finding latent factors that underlie the ratings, or making predictions about how users will rate items in the future.