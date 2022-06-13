Consider the Pandas DataFrame df below. Convert the columns math and chemistry from wide to long format.

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
