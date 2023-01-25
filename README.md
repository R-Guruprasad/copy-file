# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a text file as firstfile using with open command
### Step 2: 
Open another text file as secondfile using with open command
### Step 3: 
Using for loop , reading the content inside firstfile.
### Step 4:  
Copying first file in second file
### Step 5: 
Run the Program. The First file will be copyed in second file
### Step 6: 
End the program

## PROGRAM:
```python
'''
Python program for copying the contents from one file to another file.
Developed by: R.Guruprasad
Ref no: 22006697
'''
with open('textfile.txt','r') as file1:
    with open ('file2.txt','a') as file2:
        for line in file1:
            file2.write(line)
```

### OUTPUT:
![a](/pic1.png)

![a](/pic2.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.