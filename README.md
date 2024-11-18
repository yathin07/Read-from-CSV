# Date:
# Ex.No: 12 Read-from-CSV

## AIM: To write a python program for reading the csv file content

## ALGORITHM:
### Step 1: Load the CSV into a DataFrame.
### Step 2: Print the number of contents to be displayed using df.head().
### Step 3: The number of rows returned is defined in Pandas option settings.
### Step 4: Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))
```
## OUTPUT:
![384927275-c66bc82d-6749-4778-bd0f-825506fe049b](https://github.com/user-attachments/assets/4308f0fd-45fa-4db5-b075-a7a9f1475376)

![384927341-152e40f3-07f3-48b9-9e43-0c6bfad8edbe](https://github.com/user-attachments/assets/7ba0cd2b-e86b-4787-82b7-b4940115670d)

## RESULT: 
Thus the program is written to read the csv file.
