# nosql-challenge

After importing the establishments.json file, the setup code checks to ensure the file was imported with the correct collection. Once that is verified, the collection is saved to the variable 'establishments'. 

In part 2 of the setup code, "Penang Flavours" is added to the establishments collection and is updated with the proper 'BusinessTypeID'. All entries in 'Dover' are deleted. Longitude and latitude are set to data type of double. Any entries without a RatingValue are set to 'None', then the data type of RatingValue is set to integer. 

In the analysis code, four different queries are run. The first pulls all establishments with a hygiene score of 20. The second pulls establishments that have RatingValue of 4 or more. The third pulls the top 5 establishments by hygiene score, with RatingValue of 5, within 0.01 degrees latitude and longitude of Penang Flavours. The last query counts the number of establishments with hygiene score of 0 in each LocalAuthority. Each set of results is converted to a pandas DataFrame. 

Resouces:
All code was produced using notes from bootcamp course.