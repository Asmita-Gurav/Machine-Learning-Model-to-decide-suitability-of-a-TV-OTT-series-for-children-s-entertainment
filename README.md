# Machine-Learning-Model-to-decide-suitability-of-a-TV-OTT-series-for-children-s-entertainment
using NLP

Dataset used( https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download&select=tmdb_5000_movies.csv )

**Algorithm:**
1.Load dataset with the required features.

2. Perform data preprocessing to get the data in required format(as the data is in form of strings rather than numerical data). 

3.Create movie tags (as we need to find movies similar to a specific genre).

4. Select the genre as family and find the movies similar to it by using cosine similarity(as we are finding movies suitable for children). 

5.Create a final list of movies in which all the suitable movies are present.

6. Recommend the series/movie according to the suitability to the children.

