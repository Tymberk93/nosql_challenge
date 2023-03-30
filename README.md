# nosql_challenge
##Module 12

### Instructions: </br>
<b> The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles. </b></br>

To receive all points, my Jupyter notebook setup has all of the following:</br>

* Include the mongoimport command text you used to import establishments.json in a markdown cell at the beginning of your Jupyter notebook file </br>
* The mongoimport command text correctly drops any existing establishments collection before importing establishments.json into MongoDB </br>
* The database is named uk_food and the collection is named establishments </br>
* Correctly imports PyMongo and Pretty Print </br>
* An instance of the Mongo Client is created </br>
* Lists the databases you have in Mongo, which includes uk_food </br>
* Lists the collection(s) in the uk_food database, which includes establishments in the output </br>
* Uses find_one() and pprint to display one document in the establishments collection </br>
* The establishments collection is assigned to a variable </br>
* The supplied data for the "Penang Flavours" restaurant is correctly inserted into the establishments collection </br>
* A query is performed to find the BusinessTypeID for "Restaurant/Cafe/Canteen" and returns only the BusinessTypeID and BusinessType fields </br>
* The "Penang Flavours" document is updated with the correct value for BusinessTypeID </br>
* A query is correctly performed to delete all the documents in the collection where "Dover Local Authority" is the value for LocalAuthorityName </br>
* A count_documents() check is performed before and after the removal of the Dover documents to ensure the documents were removed </br>
* An update_many() query is performed to convert the latitude and longitude fields from strings to decimal numbers </br>
* A query is correctly performed to find the establishments with a hygiene score of 20 </br>
count_documents() is used to list the correct number of documents </br>
* The first result is printed using pprint </br>
* The results are converted to a Pandas DataFrame and displays the first 10 rows </br>
* A query is correctly performed to find the establishments in London with a RatingValue greater than or equal to 4 (4 points)
* The query uses the $regex operator to locate the London establishments </br>
count_documents() is used to list the correct number of documents </br>
* The first result is printed using pprint </br>
* The results are converted to a Pandas DataFrame and displays the first 10 rows </br>
* A query is correctly performed to find the establishments within 0.01 degree of the "Penang Flavours" restaurant </br>
* The query also limits the results to establishments with a RatingValue of 5 </br>
* The query uses the sort() method in PyMongo to sort in ascending order on the hygiene score </br>
* The query uses the limit() method in PyMongo to limit the results to 5 </br>
* All five results are printed using pprint </br>
* The results are converted to a Pandas DataFrame and displayed </br>
* An aggregation pipeline is built to include a match query, group, and sort </br>
* The match query matches documents with a hygiene score of 0 </br>
* The group step of the pipeline is grouped on LocalAuthorityName and counts the number of documents </br>
* The sort step of the pipeline sorts the count of the documents in descending order </br>
* The aggregation pipeline is correctly sent to the aggregate() method </br>
* The results from the aggregation query is cast as a list and then saved to a variable </br>
* The first ten results are printed using pprint </br>
* The results are converted to a Pandas DataFrame and displays the first 10 rows </br>

### <i> in order to re-run a piece of starter code. it is necessary to drop the database, importing .json again is needed as well. </i>
