# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
mport pandas as pd
### Step 2:
 read the csv file using read_csv method.
### Step 3:
use head and tail method to get the required contents from the file
### Step 4:
use len() method to count the number of rows and columns
### Step 5:
 print the output

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('datacsv.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of colunms:",len(df.axes[1])
```

## OUTPUT:
![output](https://github.com/ILAIYADEEPAN/Read-from-CSV/assets/147473334/6c5f3401-cf8b-41a5-86ae-ad9e91f9a76c)

## RESULT:
Thus the result was successfully verified

