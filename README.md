# Web-Scrapping-with-API
In this project you will scrape a table from a webpage and store the results in a data frame.
(Let’s call it DF1.) This table must have at least 30 records.
You will then use the values from ONE column of this dataframe as parameters to make
requests to a relevant API of your choice. On each request the API must return at least 5 pieces
of information for that query value. That is, if there are 50 values in the data frame column, you
will make 50 different requests to the API - one for each value in the column. Store the 5 pieces
of data returned from the API in another data frame. (Let’s call it DF2). Be sure to give all data
frame columns appropriate names.
Merge the two data frames horizontally (side by side) into a third data frame. (let’s call it DF3).
DF3 will contain information from both DF1 and DF2.
Let’s consider the following example for this project.
-Scrape a table which has data for the most populated cities in the world. This table will
probably have the name of the city, the population, the total land area, and country. Store this
data in a data frame.
-Use the names of the cities in the table you just scraped as query values for the weather API.
That is, for each city in the table you just scraped, make a call to the weather API to get the
relevant max temperature, min temperature, rainfall amount, humidity, and UV index for that
particular city. Store this data in a separate data frame
-Combine the two data frames into a third data frame
-Display/Print the combined data frame
-Print the description statistics for the combined data frame.
-Export the combined data frame to a csv file.
-Submit your code, csv file, and a one page report explaining how your analysis would be
helpful towards solving a relevant problem.
