# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns.

### Step 5:
Print the output.

## PROGRAM:
```
'''
DEVELOPED BY : Athmaj Venugopal
REGISTER NUMBER : 22007603
'''
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```

## OUTPUT:
![csv1](https://user-images.githubusercontent.com/118753139/214772734-9a48b376-931e-488d-b455-0f9413d431b5.png)


## RESULT:

A python program to read data from CSV files has been created successfully.
