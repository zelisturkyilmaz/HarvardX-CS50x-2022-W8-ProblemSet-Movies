# CS50's Introduction to Computer Science
## HarvardX - CS50x
### Week 8 Problem Set - Movies
<hr>


### Assignment and Requirements:
Provided by movies.db, a SQLite database that stores data from IMDb about movies, the people who directed and starred in them, and their ratings. 
In a terminal window, run sqlite3 movies.db so that executes queries on the database.


#### Execution:

In a terminal window, run 

```
$ sqlite3 movies.db
```

when ```sqlite3``` prompts you to provide a query, type 

```
.schema
``` 
and press enter. 
This will output the ```CREATE TABLE``` statements that were used to generate each of the tables in the database. By examining those statements, one can identify the columns present in each table.
