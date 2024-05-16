# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2: 
Enter the input values
 
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments

### Step 4: 
Run the program 

### Step 5:
 Input the values

### Step 6: 
End the program

## PROGRAM:
def fun(filename):\
    fp=open(filename)\
    for line in fp:\
        NoOfWords=0\
        word=line.split()\
        NoOfWords+=len(word)\
    print("No of words in file",NoOfWords)\
filename=input("Enter the filename")\
fun(filename)

### OUTPUT:
![alt text](image.png)



## RESULT:
Thus the program is written to find the word count from a text.
