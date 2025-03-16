# Movie Recommendation System

### Our aim from this project is to create a movie recommendation system that gives a list of movies taht are same as the given movie.

## Data

* movies_data_set-> tmdb_movies_data
* movies_credits_data-> tmdb_creidts_data
  
## Method

Each movie is given a set of tags, and all the movies are checked for similarity with each other based on the tags. Then the system recommends the movies with the highest similarity score.

## Process

The two sets have different data about same movies, so lets merge these two sets to a single set that contains all the data required for a movie.

Now, we have a data that has title,id,credits,release_year,budget,revenue, and many. Now we will choose the columns which will be useful for recommendation.

Now, after choosing the columns we are making a new dataset with only these columns.

Firstly, we need the information that are used to form the tags. 

Lets start with getting information for the tags. 

We get tags which has the actors, director, genres. 

We can use these tags along with overview( story of the movie), so that we can find all the tags that ar relevant to the movie.

We finally train the model and then test it.
