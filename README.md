# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
###step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The four function is used to take each line from the main file.

### Step 6:
The four function is used to take each line from the main file.

## PROGRAM:
```
#Developed by: MITHUN MS
#Reference no: 22008364
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
```
### OUTPUT:
![Screenshot_20230126_045924](https://user-images.githubusercontent.com/118344695/214824988-17a987fb-fa25-4820-8882-e046f0ce53d8.png)
![Screenshot_20230126_045936](https://user-images.githubusercontent.com/118344695/214825002-38a114ca-b8be-44d8-972d-4b8546a557c9.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
