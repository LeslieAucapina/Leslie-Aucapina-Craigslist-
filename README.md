# Leslie-Aucapina-Craigslist
The objective of this project is to create a data warehouse for Craigslist job listings in the New York metropolitan area 

# Sourcing
The final data presented is web-scraped from Craigslist.org and focuses on job postings from April 13 to May 14
A dictionary was created to reflect the data source 

# Storage
Azure Blob Storage was used for storing the data 

# Modeling 
Dimensional Modeling was done using DBSchema and updated to reflect consistent formatting and new dimensions created throughout the project 

# Transformation
A hand-written ETL process was performed with Python Script and the data was cleaned by removing nulls and reformatting
Transformations were executed such as splitting variables and creating dimension data. Mapping was also executed 

# Modeling 
Postgres was used for the data warehouse and it was created with DBSchema producing the script for its schema.
Datagrip was also used for maintenance
Data was loaded into the data warehouse after mapping it on Python Script. It was done with the database connection URL and SQLAlchemy 

# Serving Data 
To conduct insights and visualization Tableau Desktop is used and connected to the Postgre data warehouse

