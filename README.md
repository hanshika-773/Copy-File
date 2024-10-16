# Date:
# Ex.No 11: Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Define the function as copy with arguements as existing file name and new file name.

### Step 2: Open the existing file to read.
 
### Step 3: Open the new file to write.

### Step 4:  Copy the contents from existing file to new file.

### Step 5: Get the inputs from the user for existing file and new file. Call the function.

### Step 6: End the program.

## PROGRAM:
```
##Developed By: Hanshika Varthini R
##Reg No: 212223240046
with open("text.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line=f1.read()
        f2.write(line)
```
### OUTPUT:
![Screenshot 2024-10-16 163129](https://github.com/user-attachments/assets/a4ba64a3-c6d8-4105-b1d1-1fbd4efa6045)

![Screenshot 2024-10-16 162924](https://github.com/user-attachments/assets/bc698d95-a9fd-4e8c-be95-576a25487a6e)

![Screenshot 2024-10-16 162919](https://github.com/user-attachments/assets/c08f789e-63df-4dc8-ba07-39db57811323)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
