# Read-from-CSV

## AIM:
to write the pythin program to reading from CSV
## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
Read the csv file using csv_method
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Display the result

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![293445863-2d4c49cb-709c-4690-8068-4409eb7a5281](https://github.com/nainamohamed09642/Read-from-CSV/assets/151916360/1bd56826-5eaa-44df-ac4c-7f88bb09294f)

## RESULT:
Successfully the the pythin program to reading from CSV.

