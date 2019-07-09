#### Brief project description
The goal of this data pipeline is to transform data that is presented as JSON files to relational database, so the data analytics team is able to analyze ans query the data using SQL language.
We have 2 datasets: song dataset and log dataset. Using these datasets we need to analyze the songs and the user activity and build Sparkify database. Both of these datasets contain JSON-files which we need to open and process their data and put it into the appropriate tables. The file create_tables.py creates all the tables and the file etl.py inserts the data into them.

#### HOW TO USE
Step 1: create tables.
**USAGE**: python create_tables.py
Step 2: load data in JSON format and insert it to our database.
**USAGE**: python etl.py

#### DUPLICATIONS
Duplications in data are ignored, but only for **users** table the level will be updated


