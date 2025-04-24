# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Augment the matrix A with the identity matrix I → [A | I].

### Step 2: Use row operations to make the left side (A) into the identity matrix

### Step 3: Continue row operations until the left side is I 

### Step 4: The right side of the matrix is now A⁻¹.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: PRALAYAKAVERI RAJA
#RegisterNumber: 212224230202

import numpy as np
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(A)
print(result)
```
## Output:
![image](https://github.com/user-attachments/assets/6aee790d-cf79-4cef-a0ee-c499db341970)

## Result:
Thus the inverse of given matrix is successfully solved using python program

