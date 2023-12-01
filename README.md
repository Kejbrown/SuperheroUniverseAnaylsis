# SuperheroUniverseAnaylsis
If you are unable to open database or CSV files, clone the repository or download the CSV files here.
Overview: 
The purpose of this project is to demonstrate a simple data analysis using Python and SQL: 
1. Loaded data by Setting up a Local Database and read data with SQLITE/SQLAlchemy
2. Cleaned both data sets(Marvel data and DC Data) by removing unwanted fields

Instructions
Fork and clone this repo.
Create a virtual environment and install the required libraries in requirements.txt.
Download the SQLite database from Kaggle and save it to the project directory.
Run the 01_explore.ipynb notebook.
Demo 1: Explore the data
View the gitignore updates- ignoring the settings.json (sqlite extension) and database.sqlite files
Connect to the database and list the tables and columns. Note that these queries are database-specific - they would need to be changed when using something other than SQLite.
Explore a numeric field - get a sense for the distribution
Explore a categorical field
Demo 2: Clean the data
Remove unneeded columns
Remove records with NULL values
Translate dates to Birth Month
