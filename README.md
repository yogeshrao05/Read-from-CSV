# Read-from-CSV

## AIM:
To read from nba.csv file and the print the result.
## ALGORITHM:
### Step 1:
Read the CSV file using read_csv method.
### Step 2:
Use head and tail method to get the required contents from the file.
### Step 3:
Use len() method to get the number of rows and columns.
### Step 4:
Print the output.
## PROGRAM:
```
'''
Developed by: yogesh rao S D
Register Number:212222110055
'''
import pandas as p
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:

![ex-6](https://github.com/yogeshrao05/Read-from-CSV/assets/122008288/dbe0303c-a8f6-446d-aba6-60e42d87659a)

## RESULT:
Thus,the experiment was executed successfully.
