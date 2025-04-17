# Netflix-data-analysis

# In this project, we are going to analyze netflix data and answer the following questions --->


1) What is the most frequent genre of movies released on Netflix?
2) What genres has highest votes?
3) What movie got the highest popularity? what's its genre?
4) What movie got the lowest popularity? what's its genre?
5) Which year has the most filmmed movies?


Exploration Summary
we have a dataframe consisting of 9827 rows and 9 columns.
our dataset looks a bit tidy with no Nal nor duplicated values.
Release_Date column needs to be casted into date time and to extract only the year value.
Overview, Original_Languege and Poster-Url wouldn't be so useful during analysis, so we'll drop them.
there is noticable outliers in Popularity column
Vote_Average bettter be categorised for proper analysis.
Genre column has comma saperated values and white spaces that needs to be handled and casted into category. Exploration Summary


Conclusion
Q1: What is the most frequent genre in the dataset?
Drama genre is the most frequent genre in our dataset and has appeared more than 14% of the times among 19 other genres.
Q2: What genres has highest votes?
we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the highest popularity among fans by being having more than 18.5%
movies popularity
Q3: What movie got the highest popularity? what's its genre?
Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action, Adventure and Sience Fiction.
Q3: What movie got the lowest popularity? what's its genre?
The united states, thread' has the highest lowest rate in our dataset and it has genres of music, drama, 'war', 'sci-fi' and his
Q4: Which year has the most filmmed movies?
year 2020 has the highest filmming rate in our dataset.
