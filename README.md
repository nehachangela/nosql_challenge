# nosql_challenge
For this challenge, I have beeen working with your MongoDB database for the Eat Safe, Love food magazine project. Here's a summary of the steps I've taken and the queries I've performed for the exploratory analysis:
Database Setup:
•	Imported necessary libraries, including PyMongo and MongoClient, pprint and pandas, in the Jupyter notebook.
•	Confirmed the existence of the "uk_food" database and the "establishments" collection within it.
•	Used find_one and pprint to display a sample document from the "establishments" collection.
•	Assigned the "establishments" collection to a variable for further use.
Database Updates:
•	Added a new halal restaurant in Greenwich to the "establishments" collection and updated its BusinessTypeID.
•	Removed all documents associated with the "Dover" Local Authority and confirmed their deletion using count_documents.
•	Converted string-based number values (latitude, longitude, RatingValue) to numeric formats.
Exploratory Analysis:
•	I designed specific queries to addressed questions posed by Eat Safe, Love:
•	Identified establishments with a hygiene score of 20.
•	Located establishments in London with a RatingValue of 4 or higher.
•	Determined the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, in proximity to the new restaurant "Penang Flavours" using latitude and longitude.
•	Aggregated establishments with a hygiene score of 0 by Local Authority area, sorted the results, and displayed the top ten areas.
•	Used count_documents to quantify the number of documents in the results.
•	Transformed query results into Pandas DataFrames for efficient data manipulation and analysis.
Overall, my approach is thorough, and I've successfully answered the specific questions posed by the magazine editors. This analysis will provide valuable insights for Eat Safe, Love in deciding which establishments to focus on for future articles. If you have any further questions or need additional analysis, feel free to ask!
