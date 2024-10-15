# EXP 9: Word-Count
## DATE:
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program.

### Step 2: 
 Create a file story.txt in anaconda navigator.
### Step 3: 
Write a program to count the number of words in a text file.
### Step 4:  
Run the program.
### Step 5: 
Print the output.
### Step 6: 
End the program.
## PROGRAM:
```
# Word count in a Text file
# Developed by: PREETHI A K
# Register number: 212223230156
num=0
with open ("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words in the file is",num)
```

### OUTPUT:
![image](https://github.com/user-attachments/assets/350a5de8-be8e-4454-b767-57171c7dd9a2)
![image](https://github.com/user-attachments/assets/795a657a-2eeb-4e21-8506-508c8a2dc4aa)




## RESULT:
Thus the program is written to find the word count from a text.
