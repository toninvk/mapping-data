# mapping-data
Coursera Lesson 2: Mapping Data to Python

# wine-ratings.ipynb 

# First steps
First, the script imports the json and pandas packages.
Using pandas 'read_csv', the csv file 'wine-ratings-small.csv' is loaded in the notebook as a pandas dataframe. To check if the data was imported correctly, the first few rows of the data frame are printed using .head().
# Retrieve variety, rating and region values
Next, an empty dictionary is created. The values in variety, rating and region columns are extracted from each row of the dataframe using a for loop. The values from each row are added to a list object. The row index is used as a key and the list object is added as the value to the dictionary. As a result, the for loop returns a dictionary featuring the type of wine, wine score range and region of each row of the data set. 
# Serializing json
Then, create a new JSON file 'wine-ratings-small.json' using a with statement and writing mode.
