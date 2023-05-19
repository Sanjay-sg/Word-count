# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Give a input of file name(file should exits in device)

### Step 2:
Assign a varaible for count the words 
 
### Step 3: 
Open the file with read a mode

### Step 4:  
Using for loop count the words by using split function

### Step 5: 
Print the count of words

### Step 6:
End the programe 

## PROGRAM:
```
''' Program to count the words in a file
Developed By: Sanjay G
Register number:212222230131'''
fname=input('enter the file name:')
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of  words: ",num_words)
```

### OUTPUT:
![image](https://github.com/Sanjay-sg/Word-count/assets/119559022/106199dc-8cde-44f1-ae1e-b5f66db275ce)


## RESULT:
Thus the program is written to find the word count from a text.
