# nosql-challenge

Purpose:  
To evaluate the ratings data for the food magazine "Eat Safe, Love".  Need to import the data from a json file and name the database and collection.  Then modify the database by adding an establishment, modifying records in the collection, and updating fields to a different data type.  After modifying the data, run different queries to provide information that the food magazine has requested.

Process:
I used a lot of the information that was discussed in class over the three days we learned about NoSQL databases.  Most of the code I used came from the various lessons and activities from day two and three.  The one area of struggle was question 3 "What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours".  After researching how to combine the longitude and latitude with the degree search, I found guidance to handle this issue from the https://gis.stackexchange.com/ site.  Along with the example from the site to add and subtract the distance from the longitude and latitude with the degree search, I included the regex statements (from class instruction) to fine the values less than and greater than to include establishments in all directions of the restaurant.  


Resources:
https://gis.stackexchange.com/questions/257705/add-distance-to-a-latitude-or-longitude
https://www.geeksforgeeks.org/python-mongodb-delete_many/
https://www.mongodb.com/docs/manual/reference/method/db.collection.deleteMany/
https://www.mongodb.com/docs/manual/reference/operator/query/type/
