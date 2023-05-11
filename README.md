# nosql-challenge

[Parts 1 & 2](https://github.com/chelseapickett/nosql-challenge/blob/main/Starter_Code/NoSQL_setup_starter.ipynb) of this challenge import a database of restaurants 'uk_food' with a collection of 'establishments'. The database is updated with the following changes:
- A new establishment is added
- The new establishment's 'BusinessTypeID' is changed to match other establishments
- Documents with a specific location tag are deleted from the database 
- Data types are converted for longitude, latitude, and rating value 

[Part 3](https://github.com/chelseapickett/nosql-challenge/blob/main/Starter_Code/NoSQL_analysis_starter.ipynb) of this challenge analyzes the establishments in the database based on different parameters. The following parameters were used to extract data from the uk_food database:
- Hygiene score equal to 20
- London establishments with a rating greater than or equal to 4
- Top 5 establishments with a rating of 5, sorted by lowest hygiene score, nearest the new establishment added in part 2
- Top 10 number of establishments with a hygiene score of 0 sorted highest to lowest

In Part 3, the results of the queries are pretty printed and are converted to pandas dataframes for easy viewing. The last section of part 3 utilizes an aggregation pipeline to complete the complex query needed to give the desired result. 
