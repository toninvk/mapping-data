# mapping-data
Coursera Lesson 2: Mapping Data to Python

# looping-data-structures.ipynb 

# First steps
First, the script imports the pandas package.
Using pandas 'read_csv', the csv file 'wine-ratings-smal.csv' is loaded in the notebook as a pandas dataframe. To check if the data was imported correctly, the first few rows of the data frame are printed using .head().
# Retrieve variety, rating and region values
Next, an empty dictionary is created. The values in variety, rating and region columns are extracted from each row of the dataframe using a for loop. The values from each row are added to a list object. The row index is used as a key and the list object is added as the value to the dictionary. As a result, the for loop returns a dictionary featuring the type of wine, wine score range and region of each row of the data set. 

# serializing-json.ipynb 
First, import the json package from the library. Then, create a new JSON file using a with statement and the writing mode. The nested dictionary created usinf the 'looping-data-structures.ipynd' script is used as an input.
