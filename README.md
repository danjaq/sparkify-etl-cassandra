# Data Modeling with Apache Cassandra
Data Modeling with Apache Cassandra project for Udacity's Data Engineering Nanodegree. Made for Sparkify to analyze the data they've been collecting on songs and user activity on their new music streaming app.

## Procedure
Code is contained in "Sparkify_ETL_EventData.ipnyb". A full run of this file will:
1. Process the event data to extract the needed data.
2. Create the tables and insert the data.
3. Run the provided queries to show their functionality, outputing Pandas dataframes.
4. Drop the tables and close the session.

## Queries
These are the asked for queries from Sparkify:
1. Give me the artist, song title and song's length in the music app history that was heard during  sessionId = 338, and itemInSession  = 4
2. Give me only the following: name of artist, song (sorted by itemInSession) and user (first and last name) for userid = 10, sessionid = 182
3. Give me every user name (first and last) in my music app history who listened to the song 'All Hands Against His Own'
