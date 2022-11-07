# Data_2_Checks

# KC 1 Instructions

Pull in data from an API. Here's a list of public APIs that don't require Auth keys, though if you have another API you want to use feel free: https://apipheny.io/free-api/
Find and print TWO descriptive statistics about your data. This can be absolutely anything, from the mean() or sum() of a column to the number of different categories, to the number of null values in a column. We just want to see two pieces of information.
Write a query in Pandas to select a particular set of your data. You can use a mask or with .query(), but we want you to pull out a subset based on any parameter you like. This could be "show me every row where HTTPS=False" or anything else.
Select and print the SECOND AND THIRD columns of your data frame.
Select and print the FIRST 4 rows of you data frame.

# Welcome to Knowledge Check 2!

We're going to clean some data today. I would guess about 70% of data science is cleaning and wrangling data, so we want to make sure you can do it. I haven't looked through this data set at all, so we'll see if we can find some issues to clean up. Here's what you need to do to complete the knowledge check: 

1. Make a .py (or .ipynb) file that contains the following (your choice of editor does not matter!) and do the following: 
- find and access a data set in any way you want. You can use an API, a CSV, anything. 
- Fix TWO issues with the data set using techniques you've learned in class. Here are some common fixes: 
  - Remove null values 
  - Fill in null values with 0's or blanks 
  - fill in blanks 
  - fix character strings that aren't formatted correctly (you could use regex for this) 
  - correct column names if they're misnamed 
  - correct spelling (for example, you might have a Country column with an entry that says "Unted States of America".) 
  -  There are hundreds of other things you could fix depending on the issues, so don't worry about whether or not your fix "counts" for the check. It most likely will if you're fixing something.
2. Commit your changes.
3. Push your changes to GitHub, and make sure to turn in the GitHub link into Google Classroom.

