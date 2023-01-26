# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC-Anaconda - Python 3.7

## ALGORITHM: 
 Step 1: Import pandas as pd.

 Step 2: Read the csv file using read_csv method.
 
 Step 3: Use head and tail method to get the required contents from the file.

 Step 4: Use len() method to get the number of rows and columns

 Step 5: print the output.

## PROGRAM:
```
#To write a python program for reading content from a csv file.
#Developed by: Archana.k
#Register no: 22009150
with open("file.txt") as fp:
    with open("fire2.txt","W") as fp1:
        line=fp.read()
        fp1.write(line)
 ```
### OUTPUT:
![Screenshot 2023-01-26 201310](https://user-images.githubusercontent.com/118708624/214865239-fd117743-d6a1-442c-82bf-88f9310f8730.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
