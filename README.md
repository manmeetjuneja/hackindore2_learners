# hackindore2_learners
recommendation system

**This is a project which is developed with Python And Pandas**

Recommender system are of two types - 
   * context based filtering
   * collaboration filtering
  
 In context based filtering it only depend upon the context.
 example-Netflix
 In collaboration filtering it work with the technique of collaborator.
 example-amazon
 
 we will be using collaboration filtering
 
 In recommonded system we take an example of movielens,in which our attribute is user_id,rating,team_id,timespan
 With th help of mapping for we will depict for which the movie is rate by user
 for which we use a correlaion .
 we use pandas library for reading the csv dataset .
 we have to merge this dataset table with our movie table using key.
 
 Metaplot library and Seaborn are important libray viualization and characterising our data.
 With the help of these library we create a rating for dataset,then we create a rating dataframe wih average rating.
 this is a recommended system which we are gong to create 
 it Create a dataframe by which we get number of movie rated by user
we used a dataframe and set the mean value. Now we have to integrate the data,for which we make a histogram for number of rating exprss by a list.Then we create a jointplot which give combination of good scattered plot.
_Recommending simple movie_
we make a pivot table in which user idea give their rating on it.then we use a parameter called need.
Now we find the correlation between two movies from databae,for this we ue a pivot table due to which next rcommended movie is shown to the user.
