# Business Insights for a Digital Music Store

## Introduction

The [Chinook database](https://github.com/lerocha/chinook-database) contains information about a fictional digital 
music shop like a mini-iTunes store. The Chinook database includes information on the artists, songs, and albums 
from the music shop and information on the shop's employees, customers, and purchases. 
    
In this project, we will address three tasks: 

- Recommend 3 of 4 new albums from a new USA record label specializing in various genres.
- Analyzing employee's sale performance. 
- Analyzing sales by country.    


## Technical Details

- **Environment:** Utilized the ipython-sql extension to run SQL queries within Jupyter Notebook.
- **Database:** Chinook database (chinook.db) containing 11 relational tables.
- **Queries:**
  - Created views with CREATE VIEW to streamline complex queries.
  - Used SELECT statements with JOIN operations to combine data from multiple tables.
  - Employed aggregation functions such as COUNT, SUM, AVG, and MAX in conjunction with GROUP BY 
  to analyze sales performance and employee metrics.


## Dependency Versions

The Python environment used in this project can be set up in Anaconda using the python_1.yaml file.
