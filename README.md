# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys package.

### Step 2: 
Open text file using sysargv in read mode.
 
### Step 3: 
Using loop split the words.

### Step 4:  
Assign key values.

### Step 5: 
Print with the key values.

## PROGRAM:
```Python
import sys
fp = open(sys.argv[1], "r")
d={}
for i in fp:
    for w in i.split():
        if w not in d.keys():
            d[w] = 1
        else:
            d[w] +=1
print(d)
```

### OUTPUT:
![image](./Screenshot%20from%202023-01-28%2014-06-17.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
