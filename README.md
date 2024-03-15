# Recommendation-System

![image](https://cdn-images-1.medium.com/max/1200/1*x8gTiprhLs7zflmEn1UjAQ.png)


# Movie Recommendation System Overview

This project aims to develop a robust movie recommendation system using collaborative filtering techniques. By analyzing user preferences and behaviors, the system suggests personalized movie recommendations to users, enhancing their movie-watching experience. Leveraging machine learning algorithms and data mining methodologies, the system continuously learns from user interactions to refine its recommendations, ensuring relevance and accuracy. The project encompasses data collection, preprocessing, model development, and evaluation stages to deliver a seamless and efficient recommendation solution.


# The Age of Recommender Systems


The rapid growth of data collection has led to a new era of information. Data is being used to create more efficient systems and this is where Recommendation Systems come into play. Recommendation Systems are a type of information filtering systems as they improve the quality of search results and provides items that are more relevant to the search item or are realted to the search history of the user.

They are used to predict the rating or preference that a user would give to an item. Almost every major tech company has applied them in some form or the other: Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow. Moreover, companies like Netflix and Spotify depend highly on the effectiveness of their recommendation engines for their business and success.



# Dataset

Rating Dataset

This dataset, available at https://s3-us-west-2.amazonaws.com/recommender-tutorial/ratings.csv, contains information about user ratings for various movies. It likely includes columns such as User ID, Movie ID, Rating, and Timestamp, allowing for the analysis of user preferences and interactions with movies.


Movies Dataset

Accessible at https://s3-us-west-2.amazonaws.com/recommender-tutorial/movies.csv, this dataset comprises details about different movies. It may consist of columns such as Movie ID, Title, Genre, and Release Year, providing essential information for movie recommendation systems to understand the characteristics and attributes of each movie.

# Types of Recommender Systems


There are basically three types of recommender systems:-

Demographic Filtering- They offer generalized recommendations to every user, based on movie popularity and/or genre. The System recommends the same movies to users with similar demographic features. Since each user is different , this approach is considered to be too simple. The basic idea behind this system is that movies that are more popular and critically acclaimed will have a higher probability of being liked by the average audience.


Content Based Filtering- They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.


Collaborative Filtering- This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.
