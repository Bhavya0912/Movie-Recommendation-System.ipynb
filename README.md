# Movie-Recommendation-System

### Step-1: Importing the necessary libraries.
### Step-2: In this project i have imported the numpy and pandas libraries
### Step-3: Load the credits dataset from kaggle and find the information such as shape and info from the dataset.
### Step-4: Now Load the movies dataset from kaggle and find the shape and info.
### Step-5: Merge the two dataframes with commom column id
### Step-6: find the mean of vote_average column it will give us the average rating of each movie.
### Step-7: movies having vote count greater than 90% from the list will be taken
### Step-8: define the function as weighted rating based on the IMDB formula which will return (v/(v+m) * R) + (m/(m+v) * C) where v-vote count ,R-vote average,c-mean vote ,m-minimum votes required to be listed in chart
### Step-9: Define a new feature 'score' and calculate its value with `weighted_rating()`
### Step-10: Sort movies based on score calculated above
### Step-11: Print the top 10 movies
### Step-12: as per the popularity,budget,revenue we are getting these movies as the highest viewing rate
