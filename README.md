# mapping-data
Coursera Lesson 2: Mapping Data to Python

# looping-data-structures.ipynb 

# First steps
As a first step, the pandas package is imported.
Using pandas 'read_csv', the csv file 'wine-ratings-smal.csv' is loaded in the notebook as a pandas dataframe. To check if the data was imported correctly, the first few rows of the data frame are printed using head().
# Retrieve variety, rating and region values from data set
Next, the values from variety, rating and region columns are extracted from each row of the dataframe using a for loop and added to a list object. The row index is used as a key and the list object is added as the value to a dictionary.

# serializing-json.ipynb 
First, the json package is imported. Then, create a new JSON file using a with statement in writing mode. 
