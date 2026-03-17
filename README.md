# Python Data Foundations: Strings, Control Flow & Pandas
## The repository compose a comprehensive lab walkthrough covering Python core logic and data manipulation with Pandas. It serves as a technical reference for string processing, functional programming and relational data operations.

# Objectives
## - The goal of this lab was to transition from basic python syntax (String/Control Flow into Functional Programming (Lambdas) and finally into relational Data Management using the Pandas library.

# Tools Used
## - Language: Python
## - Libraries: Pandas (DataFrames and Series)
## - Environment: Jupyter Notebook

# Step-by-Step Process

## 1. String Engineering and Formatting
### - Case Normalization: Used .upper(), .lower() etc for data cleaning.
### - Data Validation and Proper Checking:
#### - Used .isupper() and .islower() as 'case consistencycheckers' to verify if a string already meets specific formatting requirements before further processing
#### - Applied boolean (True or False) checks like X .isalpha(), and .isdigit() to verify input types.                    
### - Structural Changes: Utilized .split(), and .Join to reformat raw text data.
### - Content Transformation: Applied .replace() to perform mass updates on specific substrings, ensuring uniformity across dataset labels or fixing formating errors.
### - Boundary Validation: Utilized .startswith() and .endswith to identify strings based on their prefixesor suffixes such as filtering file types or verifying protocol headers.
### - Interpolation: Implemented modern f-string and .format() for dynamic reporting.

## 2. Logical Control Flow & Functions
### - Branching/Logical Gating: Built decision engines using if-elif-else blocks to decide whether a string needs to be cleaned or if it is already in the correct format.
### - Automation: Developed FOR and WHILE loops to handle iterative or iterable tasks.
### - Advanced Functions: Explored the 'Boss of Functions' using *args and **kwargs for flexible parameter handling.
#### - Functional Tools: Applied lambda functions within map(), filter() and reduce() for memory efficient data processing.

## 3. Data Science with Pandas
### - Structure: Created 1D Series and 2D DataFrames.
### - Slicing: Extracted specific data subsets using indexing and Slicing techniques.
### - Relational Algebra: Executed complex data combinations:
#### - Concatenation: Stacking data vertically and horizontally.
#### -Merging/Joins: implementing Inner, Outer, Left & Right joins

# Commands Executed
##  1. String Formatting Commands: 
### - .upper(), .lower(), .isalpha(), .isdigit(), .islower(), .isupper, .split(), .join, .replace(), .Startswith(), .endswith()
## 2. Control Flow commands: 
### - if-elif-else statements, for and while loops.
## 3. Functions:
### - *args, **kwargs, Lambda functions, Build-in-Functions such as map, filter, reduce, sum, max, min etc).
## 4. Pandas and Series:
### - import pandas as pd, pd.Series(), pd.DataFrame, pd.concat
## 5. Merging/Joins:
### - .merge, .join, .drop,.groupby.

# Screenshots of Results

# Key Observations and Lessons Learned
## - Strings Stay the Same: Methods like .replace() or .upper() don't change the original text; they create a new version that you must save to a variable.
## - Checking vs. Changing: There is a big difference between methods that change text (like .lower()) and methods that just check if it's true or false (like .islower() or .isdigit()).
## - Better Searching: Using .startswith() and .endswith() is much easier and cleaner than trying to "slice" parts of a word to see if they match.
## - Easy Formatting: f-strings are the fastest and clearest way to plug variables into sentences compared to older methods.
## - The "Boss" of Functions: Using *args and **kwargs lets you build powerful functions that can handle any number of inputs at once.
## - Shortcuts with Lambda: Lambda functions work with map() and filter() to act as "mini-functions," saving you from writing long, repetitive code.
## - Smart Logic: Using if-elif-else and loops (for and while) lets the computer make decisions and repeat tasks automatically.
## - 1D vs. 2D Data: Knowing the difference between a Series (one column) and a DataFrame (a whole table) is key to finding the right data.
## - Combining Data: Picking the right Join or Merge (Inner, Outer, Left, Right) is the most important step to make sure you don't lose data when putting tables together.
## - Speed over Loops: Using Pandas to change data is much faster than using a "for loop" to go through rows one by one.
## - Cleaning First: Most data work starts by fixing text (using .replace() or .split()) before you can do any math or matching.
## - Organized Code: Importing modules keeps your workspace tidy and prevents different parts of your code from getting mixed up
