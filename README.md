# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
fname to represent the file name given

### Step 2: 
with open function to open a file 
 
### Step 3: 
text files words are splitted using split()

### Step 4:  
using for loop to count the char
### Step 5: 
char has been counted and output has been printed

## PROGRAM:
```
# Program to find the word count using command line arguments
# Developed by: franklin raj G
# register no: 23001518
fname=input("enter the file name")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('number of words:',num_words)

```
### OUTPUT:

![Screenshot 2024-01-03 000017](https://github.com/franklinraj/command-line-arguments-to-count-word/assets/148993740/a3b8edda-81b8-473c-890e-127c0b33f0a6)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
