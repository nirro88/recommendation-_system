# recommendation-_system

download the ‘movie dataset’ from the following link:
https://www.kaggle.com/rounakbanik/the-movies-dataset/version/7#

for the purpose of this model only the following data files and specified columns and consider all the additional data and columns as not relevant for the purpose of this exercise – 
-	Ratings: columns - userid, movieid, rating, timestamp
-	Movies_metadata: columns - id, title, genres

If the files are too heavy for you to process, use a sample of 20%-50% of the data (rows) 

1.	Using the specified data (above), create a list of the top 10 movies  

3.	split the data to train\test sets and evaluating the models.

4.	create two recommendation models 
•	Model 1 –
o	 Model input data (without genres column)– 
	Ratings: columns - userid, movieid, rating, timestamp
	Movies_metadata: columns - id, title
Model output – for each user (in the training set) a list of 10 movie recommendations, with the predicted rating per recommendations. 

•	Model 2 (Bonus question)- 
o	Model input data (with genres column)– 
	Ratings: columns - userid, movieid, rating, timestamp
	Movies_metadata: columns - id, title, genres
Model output – for each user a list of 10 movie recommendations, with the predicted rating per recommendations. 

4. evaluate the accuracy of each of the models you developed, using the static model  

