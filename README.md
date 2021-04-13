# Movies-ETL

### OVERVIEW OF THE ANALYSIS

This analysis helps Britta to create an automated pipeline that takes in new data, through performing the appropriate transformations, and loading the data into existing tables. The data was extracted from *JSON* and *CSV* files, properly examined and cleaned, and afterwards connection to the *PostgreSQL* database for extraction in table format which can be extracted back to *CSV* format.

The data contains information of movies, ratings and its properties in terms of its composition. The cleaned data happens to be very large that the movies table has *6,052* rows and the ratings table has *26,024,289* rows. Below are screenshots of the data in *PostgreSQL* database.

![image](https://user-images.githubusercontent.com/78067427/114503954-161d1280-9bfc-11eb-9f08-c7b38cc2d9d3.png)
![image](https://user-images.githubusercontent.com/78067427/114567015-d593b800-9c40-11eb-8265-d4be9acaaaf4.png)

