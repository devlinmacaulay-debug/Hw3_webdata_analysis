Organize the various modeling and analysis outputs in this folder.Homework 3 - Option 2 Data Wrangling/Visualization/Anlaysis

For homework 3 i chose the second option and used FRED website as my data source to pull market data
for the S&P500, NASDAQ, VIX and Dow Jones. I first created a dictionary and a function that leveraged 
that dictionary for each market indicator code and series name then ran a loop to add them to 
a complete list and ultimately a combined dataframe that could later support analysis and 
graphs/visuals. I found out that the data i was using has different amounts of data collected 
for each market indicator so I went through several iterations to get the same amount of data 
collected ultimately starting with 2017. Once that was completed I saved the data to a csv and 
looked at some summary level statistics and realized that some of the information could be drastically
different as far as range of values which was helpful when reconciling the later visuals produced.S

