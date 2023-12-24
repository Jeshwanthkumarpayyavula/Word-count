# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Instalize the value for count as zero
### Step 2: 
Using open command open the txt file to read
### Step 3: 
Use the split() command
### Step 4:  
print the counted words
### Step 5: 
End the program

## PROGRAM:
```
'''
Developed by: P.Jeshwanth Kumar
Registered number: 212223240114
'''
num_words=0
with open('Word.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))
```

### OUTPUT:
![image](https://github.com/Jeshwanthkumarpayyavula/Word-count/assets/145742402/c95d426c-1b6e-4a58-beba-bb132e53cbb5)
![image](https://github.com/Jeshwanthkumarpayyavula/Word-count/assets/145742402/4d936181-c1ac-4f70-b935-a1ad192f4181)

## RESULT:
Thus the program is written to find the word count from a text.
