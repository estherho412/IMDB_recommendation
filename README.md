# IMDB_recommendation
A hybrid version of recommendation system is built for the Movielens100k dataset (https://grouplens.org/datasets/movielens/100k/).
The recommendation system consists of 
1) Content-based (according to movie genre similarity) 
2) Collaborative-based (according to user's rating on movie, esp. Matrix factorization)

Due to the movies suggested in the Movielens100k dataset are a bit outdated,
We scraped the latest data from IMDB website to obtain the movies in various genres with highest rating and
built a content-base recommender accordingly through RASA chatbot linked with Slacks.

<img width="626" alt="rasa" src="https://user-images.githubusercontent.com/62921289/88481472-4e0cf880-cf8e-11ea-8a85-2d98078df790.png">

