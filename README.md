# Read-from-CSV

## AIM:
To write a python for reading content from a CSV file.

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
 #Developed by : VARSHINI D
 #Register number : 212223230234
 '''
 import pandas as pd
 df = pd.read_csv('nba.csv')
 print(df.head(10))
 print(df.tail())
 print("Number of rows:",len(df.axes[0]))
 print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![Alt text](csv_ss.png)

## RESULT:
Thus a python program is written to read the content of a CSV file.
