# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
 Open the text1.txt file in read mode


### Step 3: 
Create a copy.txt file using write mode


### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM: 
```
Program for copying the contents from one file to another file
Developed by: KISHORE.B
RegisterNumber: 212222110020

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
    ```
### OUTPUT:

![image](https://github.com/KISHORE22001263/copy-file/assets/121484538/aa79b71b-9970-4d0d-99d1-d885a74398e6)
![image](https://github.com/KISHORE22001263/copy-file/assets/121484538/b8ec38c4-45db-452a-8213-eb9866864695)
![image](https://github.com/KISHORE22001263/copy-file/assets/121484538/b1b613be-6821-4f45-b5c0-c81cdafaa24b)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
