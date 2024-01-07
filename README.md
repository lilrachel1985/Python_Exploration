# Python_Exploration using Pandas
Salary Analysis: #Data Exploration and Data Cleaning with Pandas# This is always the first step with any data science project. 
Let's see if we can answer the following questions:

How many rows does our dataframe have?
How many columns does it have?
What are the labels for the columns? Do the columns have names?
Are there any missing values in our dataframe? Does our dataframe contain any bad data?
Commands Used: .head() method to peek at the top 5 rows of our dataframe .shape() method to see the number of rows and columns

#Missing Values and Junk Data

df.isna() to look for NaN (Not A Number) values in our dataframe(NAN values are blank cells or cells that contain strings instead of numbers) clean_df=df.dropna()- drops the columns with null values and create a new dataframe

#Accessing Columns and Individual Cells in a Dataframe To access a particular column from a data frame we can use the square bracket notation-eg: clean_df['Starting Median Salary'] To find the highest starting salary we can simply chain the .max() method .idxmax() method will give us index for the row with the largest value..idxmin() method will give us the index for the row with the smallest value .loc()To see the name of the major that corresponds to that particular row

Questions Answered: :) What college major has the highest mid-career salary? How much do graduates with this major earn? (Mid-career is defined as having 10+ years of experience).

:) Which college major has the lowest starting salary and how much do graduates earn after university?

:)Which college major has the lowest mid-career salary and how much can people expect to earn with this degree?

