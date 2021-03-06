# Netflix_Movie_Recommendation

## Inspiration:
- This notebook provides companies(like Netflix, Amazon) to recommend **Movies** to its users where he/she will be most interested in and is likely to provide better Ratings. This is computed based on the previous reviews provided by the user.

---
## Data
- Data has been imported from Kaggle
- Code was excuted using [Kernel from Kaggle](https://www.kaggle.com/lokeshrth4617/netflix-movies-recommendation-1)
- Dataset has 24M+ rows and  2 columns
---
## Data Processing
- Data with only first 2 columns were imported.
- The number of movies present were 4499.
- Number of customer 470758
- Number of ratings given were 24053764

![](https://github.com/Lokeshrathi/Netflix_movie_recommendation/blob/master/Image/ratings1.png)

- The above graph displays the rating percentage of each ratings.
- Data has been updated as Movie_id, by adding the Movie_id as the new column.

![](Image/Screenshot%20from%202020-06-19%2018-17-48.png)
---
## Data Cleaning
- We are keeing the movies that has been **reviewed a minimum of 1799 times.**
- We have kept only those customers who have **reviewed a minimum of 52 times**
- Data Size after trmming: **(17337458, 3)** 

## Machine Learning Algorithm
- SVD was applied on the dataset.

![](Image/Screenshot%20from%202020-06-19%2018-26-38.png)

- We find the prediction for the user_id = 712664 and has given a rating of 5, we merge the movies dataframe to diplay only the movie_id and the name of the movie.

## Prediction
- We finally predict the movies that should be recommended to the users and estimate the rating that might be given by the user.

![](Image/Screenshot%20from%202020-06-19%2018-32-01.png)



