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
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
#Program for copying the contents from one file to another file
#Developed by: P.Bharathraj
#RegisterNumber: 212223230031
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copy.txt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![image](https://github.com/Bharathraj2006/Copy-File/assets/152376845/470d0be7-3edf-4a68-a651-07f1cef13a46)
![image](https://github.com/Bharathraj2006/Copy-File/assets/152376845/56062758-5449-4703-92d0-e6de79bad568)
![image](https://github.com/Bharathraj2006/Copy-File/assets/152376845/b7728d6c-8a81-4329-abe4-a629524c96d1)
## RESULT:
Thus the program is written to copy the contents from one file to another file.
