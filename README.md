# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_inverse(), we can find the rank of the given matrix
### Step 4: 
End the program

## Program:


#Program to find the inverse of a matrix.

#Developed by: D. R. Vinuthna

#RegisterNumber:21005742

import numpy as np


A=np.array([[2,1,1],[1,1,1],[1,-1,2]]) 

s=np.linalg.inv(A)


print(s)
## Output:
![output](https://github.com/VINUTHNA-2004/INVERSE-OF-A-MATRIX/blob/main/inverse%20of%20matrix.PNG?raw=true)
## Result:
Thus the inverse of given matrix is successfully solved using python program

