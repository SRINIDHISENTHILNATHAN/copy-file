# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Create two empty files.
### Step 2: 
 
 In one file.txt enter some content and save the file.
### Step 3: 

 In other file1.txt file read the file.txt using .read() build in function.
### Step 4:  

Next ope file1.txt in write mode.
### Step 5: 

 Copy file.txt using copy() funtion.
### Step 6: 

Run the program.
## PROGRAM:
```
Devloped by: SRINIDHI SENTHIL
reference no: 22001408

with open('word_count.txt','r') as f1:
    with open('word_file.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:

![image](https://user-images.githubusercontent.com/121373170/214642266-78d505dc-30a5-4d5b-a868-7bacca0d1caf.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
