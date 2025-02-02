# Read-from-CSV

## AIM:
To write a Python Program to read the csv file

## ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_csv method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns.

Step 5:
Print the output

## PROGRAM:
~~~
import pandas as pd
df=pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print('No. of Columns:',len(df.axes[1])) 
print('No. of Rows:',len(df.axes[0]))
~~~

## OUTPUT:
![Code](csvimg1.jpeg)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
