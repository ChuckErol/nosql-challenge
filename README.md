# Nosql-Challenge #

## Importing Database:
- Imported the data provided in the 'establishments.json' file from your Terminal. Name the database 'uk_food' and the collection 'establishments' using the terminal.
- After importing the libraries I need: PyMongo and Pretty Print (pprint), created an instance of the Mongo Client.
- Confirmed that I created the database and loaded the data properly. 
- Listed the databases I have in MongoDB. Confirmed that uk_food is listed.
- Listed the collection(s) in the database to ensure that 'establishments' is there.
- Found and displayed one document in the 'establishments' collection using 'find_one' and display with 'pprint'.
- Assigned the 'establishments' collection to a variable to prepare the collection for use.

## Update the Database:
- Added the new halal restaurant just opened in Greenwich, but hasn't been rated yet.
- Update the new restaurant with the BusinessTypeID I found.
- Checked how many documents contain the Dover Local Authority. Then, removed any establishments within the Dover Local Authority from the database, and check the number of documents to ensure they were deleted.
- Used 'update_many' to convert 'latitude' and 'longitude' to decimal numbers.
- Used 'pdate_many' to convert 'RatingValue' to integer numbers.

## Exploratory Analysis:
- Used 'count_documents' to display the number of documents contained in the result.
- Wrote a query to answer "Which establishments have a hygiene score equal to 20?".
- Wrote a query to answer "Which establishments in London have a RatingValue greater than or equal to 4?".
- Wrote a query to asnwer "What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?".
- Wrote a query to answer "How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas."

## Sources:
- Found some of my codes from previous class activities.
- I ask some questions to my classmates in Slack and during our study group meeting.
- I found some helpful information watching various YouTube videos and Stack OverFlow website