# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function for copying contents

### Step 2: 
Open the existing file
 
### Step 3: 
Open the new file in write mode

### Step 4:  
Read the data from existing file

### Step 5: 
Write the read data in to new file

### Step 6: 
Call the function and copy the contents

### Step 7:
End the program

## PROGRAM:

Developed by: SATHYAA R

Register number: 212223100052

```
def copy(fname,newfile):
    with open(fname) as fp:
        with open(newfile,'w') as fp1:
            data=fp.read()
            fp1.write(data)
copy("hello.txt","myfile.txt")
```

### OUTPUT:

![alt text](<Screenshot 2024-05-15 175838.png>)
![alt text](<Screenshot 2024-05-14 104449.png>)
![alt text](<Screenshot 2024-05-14 104435.png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
