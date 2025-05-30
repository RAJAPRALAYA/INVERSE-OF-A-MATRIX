# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
## Step 1:  Ensure the matrix is square and has a non-zero determinant.
## Step 2: Form the augmented matrix [A|I], where I is the identity matrix.
## Step 3: Use row operations to transform [A|I] into [I|A⁻¹].
## Step 4: Extract A⁻¹ from the right half of the resulting matrix.
```
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

