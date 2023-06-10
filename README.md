# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file
### Step 2: 
open the file in read mode
### Step 3: 
use for loop for counting the number of words
### Step 4:  
store the value
### Step 5: 
print the value

## PROGRAM:
```
'''
program to count the words in a file
reg number :212222110056
developed b : yuva krishna k
'''
fname=input("enter the file name ")
num_words=0
with open(fname,'r') as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print('number of words:',num_words)
```

### OUTPUT:
![uvaop](https://github.com/Yuvakrishna0/Word-count/assets/117915037/a81d95ed-111e-4e01-8b86-16c54deffb8e)




## RESULT:
Thus the program is written to find the word count from a text.
