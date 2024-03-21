# nosql-challenge
## Part 1: Database and Jupyter Notebook Set Up

    1. using importmongo command to import establishment.json file including dropping existng collection and naming uk_food as database and establishment as the collection.
    2. import MongoClient from Pymongo and Pretty Print.
    3. create an instance of the Mongo Client.
    4. list the databases in Mongo, uk_food shown in the list.
    5. list the collections in the uk_food database, establishments shown in the list.
    6. use find_one and pprint to displayt one document in the establishment collection.
    7. assign a variable to the establishment collection.

Part 2: Update the Database

    1. insert the supplied data for the "Penang Flavours' restaurant.
    2. check the new restaurant was inserted.
    3. a query is performed to find the BusinessTypeID for "Restaurant/Cafe/Canteen" and returns only the BusinessTypeID and BusinessType fields.
    4. the "Penang Flavours" document is updated with the correct value for BusinessTypeID and check the update.
    5. a query is performed to find the number (994 )of the documents in the collection where "Dover Local Authority" is the value for LocalAuthorityName before deleting them all.
    6. a count_documents() check is performed before and after the removal of the Dover documents to ensure the documents were removed.
    7. an update_many() query is performed to convert the latitude and longitude fields from strings to decimal numbers and RatingValue to integers.

Part 3: Exploratory Analysis

    Q1: Which establishments have a hygiene score equal to 20?
    A1: Query has been performed. Based on the result, 41, such as "The Chase Rest Home" have a hypiene score equal to 20.

    Q2. Which establishments in London have a RatingValue greater than or equal to 4?
    A2: Query has been performed. Based on the result, 34 establishments in London, such as "Charlie's", have a RatingValue greater than or equal to 4.

    Q3: What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
    A3: Query has been performed. Based on the result, the top 5 establishments that meet the criteria are displayed.

    Q4: How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.

    A4: Query has been performed.Fifty six (56) establishments in each local authority area have a hygiene score of 0, including the top 10: Thanet, Greenwich, Maidstone, Newham, Swale, Chelmsford, Medway, Bexley, Southend-On-Sea, and endring.

## References/acknowledgement
This assignment has been completed primarily with reference to the course materials for Module 12. The help from the teaching team, from the Xpert Learning Assistant at Datacampspot, and from the ChatGPT are acknowledged. 

