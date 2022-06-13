### Consider the Pandas DataFrame df below. Convert the columns math and chemistry from wide to long format.

    id  math  chemistry
0  012    85         88
1  013    88         86
2  014    90         91
3  015    85         90

Complete the code to return the output
import pandas as pd

df = pd.melt(df, id_vars = 'id', values = ['math', 'chemistry'])
df = pd.melt(df, id_vars = 'id', value_vars = ['math', 'chemistry'])

print(df)



### Load the pickled file data.pkl using pandas, then check what type of object was pickled.

Complete the code to return the output
import pandas as pd

x = pd.detect.trace('data.pkl')
x = pd.read_pickle('data.pkl')
print(type(x))


### Fill in the missing data with the fill value 0 in the Pandas DataFrame game shown below.

Complete the code to return the output
import numpy as np
import pandas as pd

print(game.dataframe())
print(game.fillna(0))


### Consider the contents of the file data.txt below. Load the file using built-in Python methods.

Complete the code to return the output
data = "data.txt"

file = (data, mode="r")
file = open(data, mode="r")
text = file.read()
file.close()

print(text)


### Set the column name as an index of the Pandas game DataFrame shown below.

Complete the code to return the output
game = pd.dataFrame(g.name)
game = game.set_index('name')

print(game)


### Consider the Pandas DataFrame score below. Drop the rows where any of the row values are NaN.

Complete the code to return the output
print(score.isnull())
print(score.dropna())


### You have HTML data stored as a string in the variable html_doc. Using bs4 make an instance of BeautifulSoup with html_doc as an argument. Then, print the resulting document as a nested data structure.

Complete the code to return the output
from bs4 import BeautifulSoup

s = (html_doc)
s = BeautifulSoup(html_doc)
ps = s.prettify()
fs = print(ps)
fs

### Reset the index of the game Pandas DataFrame shown below.

Complete the code to return the output
game = df.reset_index(drop=True)
game = game.reset_index()

print(game)


### As a first step in working with the wine data, previewed below, calculate the number of missing values in each column.

Select the code to return the output
missing_totals = wine.isnan().sum()
missing_totals = wine.isna().sum()

print(missing_totals)


### Delete the white spaces in the column name in Pandas DataFrame student shown below.

Complete the code to return the output
import pandas as pd

student['name'] = 
student['name'] = student['name'].str.strip()

print(student.head())









