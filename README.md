# nosql-challenge

# Part 1: Database and Jupyter Notebook Set Up                  
    * Imported the 'establishment.json' through compass. inserted the database as 'uk_food' cand the collection as 'establishments'.
    * Libraries 'PyMongo' and 'Pretty Print(pprint)' were imported.
    * Instance was created of the Mongo Client.
    * Confirmed that everything was loaded properly:
        * Database: uk_food
        * Collections: establishments
        * Found and displayed documents in 'establishments' using 'find_one' and displayed with 'pprint'
    * Assigned the collection 'establishments' to a variable in order to prepare it for use.
# Part 2: Update the Database
    * Added/created the information to add to the database in order to insert the new restaurant(Penang Flavours).
    * Found the 'BusinessTypeID' for "Restaurant/Cafe/Canteen so that we could only return the fields: 'BusinessTypeID' and 'BusinessType'.
    * Updated the new restaurant with the 'BusinessType' that was found.
    * Checked how many documents contained the "Dover Local Authority"(994). Then took those documents out because the magazine wasn't interested in these establishments.
    * Updated the 'latitude' and 'longitude' with converting them to a decimal. Also updated the 'RatingValue' and converted it to integer numbers.
# Part 3: Exploratory Analysis
    * Answered the questions that "Eat Safe, Love" had in order to help them find locations the wished to visit as well as avoid:
        * Which establishments have a hygiene score equal to 20?
        * Which establishments in London have a RatingValue greater than or equal to 4?
        * What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
        * How many establishments in each Local Authority area have a hygiene score of 0? 
            * Found and sorted the results from highest to lowest and printed out the top ten local authority areas.

# Going back and reviewing on some classwork really assisted/guided me through.

# Some help from classmate Chris Canala for the setup portion when having to change the data type.