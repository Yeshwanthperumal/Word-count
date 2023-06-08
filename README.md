# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0

### Step 2: 
open it with txt file

### Step 3: 
Give range for i

### Step 4:  
Then nxt split the words

### Step 5: 
count the number of words

### Step 6: 
Giving print statement for getting output

## PROGRAM:
```
# Program to count the no. of words in a file.
# Developed by YESHWANTH P
# Reg.no: 212222230178
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```

### OUTPUT:
![Screenshot 2023-06-08 224224](https://github.com/Yeshwanthperumal/Word-count/assets/119476088/0e330324-8084-4ba3-94fe-71a91a3cdeed)

## RESULT:
Thus the program is written to find the word count from a text.
