# movie_recommendation_system

# Types of Recommender Systems -
There are two major approaches to build recommender systems: Content-Based Filtering and Collaborative Filtering:

# 1. Content-Based Filtering
        In content-based filtering, the similarity between different products is calculated on the basis of the attributes of the products. For instance, in a content-based movie recommender system, the similarity between the movies is calculated on the basis of genres, the actors in the movie, the director of the movie, etc.

# 2. Collaborative Filtering
        Collaborative filtering leverages the power of the crowd. The intuition behind collaborative filtering is that if a user A likes products X and Y, and if another user B likes product X, there is a fair bit of chance that he will like the product Y as well. Take the example of a movie recommender system. Suppose a huge number of users have assigned the same ratings to movies X and Y. A new user comes who has assigned the same rating to movie X but hasn't watched movie Y yet. Collaborative filtering system will recommend him the movie Y.
        
The system developed is a very simple movie recommender system in Python that uses the correlation between the ratings assigned to different movies, in order to find the similarity between the movies. The dataset for the system is in the files 'links.csv', 'ratings.csv', 'tags.csv', and 'movies.csv'.

# The python libraries mainly used are:
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborn
