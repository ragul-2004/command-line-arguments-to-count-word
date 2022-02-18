# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.
### Step 2: 
Use the open() by getting the file name with "sys.argv[1]" which means the first index of given argument.
### Step 3: 
Iterate the content of the file using for loop.
### Step 4:  
Split the contents into each line using .split() function.
### Step 5: 
Iterate the list of lines and increment the value of variable (word) each time.
### Step 6: 
Run the program.
## PROGRAM:
~~~
#Program to command line arguments to count word.
#Developed by: Syed Abdul Wasih H
#Register number: 212221240057
import sys
fp =open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Number of Words : ",len(words))
~~~
### OUTPUT:

![output](1.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
