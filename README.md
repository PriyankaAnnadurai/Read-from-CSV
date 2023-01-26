# Read-from-CSV

## AIM:
To read files from csv files using python program.

## ALGORITHM:
### Step 1:
First we want to import pandas.
### Step 2:
Then we want to create csv file.
### Step 3:
Both python and csv files are in the same folder.
### Step 4:
Then write the revalent code in the python file
### Step 5:
Then check the result.


## PROGRAM:
```
# To read files from csv files using python program.
# Developed by: Priyanka.A
# Register no: 22008829

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![output](./img/vs.jpg)
![output](./img/vs2.jpg)

## RESULT:
The result for read from csv is came successfully.