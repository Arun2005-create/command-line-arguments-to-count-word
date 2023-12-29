# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.
### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3:
Read the file using read() method.
### Step 4:
Use split() method to split the file content into words.
### Step 5:
Use len() to find the total words.
### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: Arun KUMAR B
# Register number: 2122232320021
import sys
fp= open(sys.argv[0])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```

### OUTPUT:
![Screenshot 2023-12-29 175825](https://github.com/Arun2005-create/command-line-arguments-to-count-word/assets/138849356/22dfa63b-950b-47b6-9365-39f8780aa39b)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
