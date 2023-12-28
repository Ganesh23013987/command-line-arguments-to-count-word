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
Pass the filename as the first argument after the name of script. Open the file as file1.txt
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
with open('C:/Users/BSS/Documents/file1.txt','r') as f:
          for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)
```
### file1.txt:
<img width="308" alt="cmd line arg  in file" src="https://github.com/Ganesh23013987/command-line-arguments-to-count-word/assets/147473768/50112921-1d80-443f-adfb-4f2cddac8eac">


### OUTPUT:

![Alt text](<cmd line arg output.png>)

### command line arguments output:
<img width="674" alt="cmd output" src="https://github.com/Ganesh23013987/command-line-arguments-to-count-word/assets/147473768/c51556c3-db0a-4892-94b7-f8cc291061dd">


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
