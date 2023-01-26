# Read-from-CSV

## AIM:

## ALGORITHM:

step 1:
Import pandas module as pd.

Step 2:
Using pd.read_csv() method read the CSV file.

Step 3:
Using df.head() print the first 10 rows of the CSV file.

Step 4:
Using df.tail() print the last 5 of the CSV file.

Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

Step 6:
End of the Program

## PROGRAM:
To write a python program for reading content from a CSV file.
Developed by: Rakesh J.S
Register Number: 22009339

import pandas as pd
df = pd.read_csv('data1.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

## OUTPUT:
![eig](3.png)
## RESULT:
To write a python program to read contents from a CSV file.
