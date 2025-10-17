# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as it provides matrix operations.
### Step 2: 
Create the matrix using numpy.array().
### Step 3:
Use numpy.linalg.det() to check if the determinant is not zero.
### Step 4: 
Use numpy.linalg.inv() if the matrix is invertible.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: aranivenkata sundara leela krishna
#RegisterNumber:212224240013

import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1755" height="2149" alt="image" src="https://github.com/user-attachments/assets/e5951ce1-f523-424a-9591-08d526475eb3" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

