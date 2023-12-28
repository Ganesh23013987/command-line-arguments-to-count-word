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
Read the file using read() method
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
'''
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: Ganesh.D
RegisterNumber:23013987
'''
import sys
count=0
with open('C:/Users/BSS/Documents/file1.txt','r')as f:
          for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```
### OUTPUT:

![Alt text](<cmd line arg output.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
