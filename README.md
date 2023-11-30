# Book_Recommendation_System

Recommendation Systems are sophisticated algorithms designed to suggest items to users based on their interests. These systems play a crucial role in online shopping platforms to boost sales by personalizing user experiences.

There are primarily two categories of recommender systems:

#### Collaborative Filtering System:   
This type of system generates recommendations from users’ past behavior, preferences, and choices. It creates a user profile model and identifies items to recommend based on similarities between user profiles and their shared interactions with items.

#### Content-Based Filtering System:  
In contrast to collaborative filtering, content-based systems focus on the characteristics of the items themselves. They recommend items by analyzing the similarity of their attributes, suggesting items that share common features.

## Objective
Develop a neural network-based book recommendation system to deliver personalized book suggestions that resonate with individual user preferences and reading habits. Implement collaborative filtering approach by creating and learning from user and book embeddings, aiming to understand and utilize the intricate patterns of user-book interactions to enhance the quality of recommendations. Focus on minimizing the mean squared error during training to improve the accuracy of predictions, with the system's success measured by its performance on unseen data, user engagement, and satisfaction metrics.


## Overview of the Dataset
While there have been notable datasets for movie (such as Netflix and Movielens) and music (like the Million Songs dataset) recommendations, book recommendations have lagged behind until the introduction of this dataset. The dataset comprises ratings for ten thousand well-known books. These ratings were sourced from the internet. On average, each book has 100 reviews, though some have less. The ratings range from one to five.

The dataset features sequential IDs for both books and users. Book IDs run from 1 to 10,000, and user IDs from 1 to 53,424. Every user has contributed at least two ratings, with a median of 8 ratings per user. Additional data includes a list of books marked as 'to be read' by users, along with book metadata such as the author and publication year, as well as various tags associated with the books.

This dataset is available on Kaggle: [Click Here to view the Dataset](https://www.kaggle.com/datasets/zygmunt/goodbooks-10k)

## Neural Network Architecture:
![image](https://github.com/ruchithareddy269/256-Project-Book_Recommendation_System/assets/64256985/1ec6a0d7-d3d2-45dd-946d-7f5fb0c3efea)





