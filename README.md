# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Decleare number of words is 0

### Step 2: open it with txt file
 
### Step 3: Give range for i

### Step 4: Then nxt split the words 

### Step 5: count the number of words

### Step 6: Giving print statement for getting output



## PROGRAM:
```num_words =0
with open('text.txt','r') as file1:
 for i in file1:
 word =i.split()
 num_words += len(word)
print("Number of words={}".format(num_words))
```

### OUTPUT:
![python 5 1](https://github.com/velupradeep/Word-count/assets/150329341/f6033c66-4649-4153-a3e7-d2b1596cda07)
![python 5](https://github.com/velupradeep/Word-count/assets/150329341/5ec1e7bc-22c6-40d7-8bac-035a8577600b)




## RESULT:
Thus the program is written to find the word count from a text.
