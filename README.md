# movie-recommender
A movie recommendation system, finding similar movies to recommend using cosine similarity

we use TheMovieDatabase(TMDB) database of 5000 movies for our application, we recommend 5 movies to the person based on the movie they have entered.

We use Content-based Recommendation, in which we recommend similar movies based on the movie they provide.

First we clean the data and perform data preprocessing to extract names of genres, keywords, cast, crew etc. 

Then we vectorise the data to perform cosine similarity on the data.

Cosine similarity is a metric used to measure how similar two items are. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.

The cosine_simliarity matrix is a numpy array with calculated cosine similarity between each movies.

We use streamlit library to create a web application for our recommender system.

Required Libraries:
1. Numpy
2. Pandas
3. ast
4. scikit-learn
5. pickle
6. Streamlit
7. Requests
