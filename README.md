# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.
### Step 2: 
 Print the number of contents to be displayed using df.head().
### Step 3: 
The number of rows returned is defined in Pandas option settings.
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program.
## PROGRAM:
```python
#To write a python program for reading content from a CSV file.
#Developed by: SRIHARAN J V
#Register Number: 212223100054

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
### OUTPUT:

![image](https://github.com/DariusRijin07/Copy-File/assets/138849120/411f7d51-d284-49db-92c6-f75ddfc374a4)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
