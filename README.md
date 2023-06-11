# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the file f1 in read mode.

### Step 2: Open the file f2 in append mode.
 
### Step 3: Copy the contents using write() with the for loop.

### Step 4: End the program.

## PROGRAM:
#Developed By: Deepika S
#Register No: 212222230028
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
            

### OUTPUT:
![py 1](https://github.com/deepikasrinivasans/copy-file/assets/119393935/5493de85-9c06-4fd1-9320-9fdd079837c0)
![py 2](https://github.com/deepikasrinivasans/copy-file/assets/119393935/f707ae7d-d7ad-4b83-87fd-fcb65f31c62c)
![py 3](https://github.com/deepikasrinivasans/copy-file/assets/119393935/e0a14ed8-3a46-49b4-9e04-b1c9dcb6edd0)

## RESULT:

Thus the program is written to copy the contents from one file to another file.
