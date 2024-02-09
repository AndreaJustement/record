# Individual No SQL project with MongoDB

This is a project in which we will use MongoDB to store data related to a Record_Company, for which we will create collections; artists, albums and songs. Where we will then develop a series of practical exercises.
## For this;
- **MongoDB Compass**: Access MongoDB Compass at:
  `http://localhost:27018`, to explore and manage the database visually.
• In this first point; Create the database, add the collections required by the statement of the different points of the exercise.
• Then some INSERT and UPDATE.
     All this through the MongoDB Compass interface.
## For the points in the exercise book below:
- **Mongo Shell**: Access the Mongo shell by running `docker exec -it mongodb-container mongo` to perform operations directly from the command line.
1. db.collection.insertOne({ key: "value" }): Inserts a new document into a collection.
2. db.collection.insertMany([{ document1 }, { document2 }, ...]): Insert multiple documents into a collection at the same time.
3. db.collection.updateOne({ filter }, { $set: { key: "newValue" } }): Updates a document in a collection that matches the specified filter.
4. db.collection.find({ filter }): Queries for documents in a collection that match the specified filter.
5. db.collection.deleteOne({ filter }): Delete a document in a collection that matches the specified filter.
Conclusion:
In conclusion, the work done in MongoDB has allowed me to understand and apply a variety of concepts and techniques for managing data in a NoSQL database. Through hands-on exercises, I have learned how to model data, perform CRUD operations, perform advanced queries using aggregation, and work with indexes to improve query performance.
Some of the key concepts I have explored include flexible data modeling using JSON documents and Commands by Console. Without further ado, it seems to me that it was a good start, for the first steps in the knowledge of modeling this type of non-relational Database. In addition to good practice, to acquire knowledge of the use of different technological tools, which allows us to develop them.
