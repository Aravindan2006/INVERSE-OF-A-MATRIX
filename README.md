# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculationc
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv, we can find the rank of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: ARAVINDAN D
#RegisterNumber:212223240012


import numpy as np

A = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])

rank = np.linalg.inv(A)

print(rank)
```
## Output:
![Screenshot (20)](https://github.com/Aravindan2006/INVERSE-OF-A-MATRIX/assets/151760062/134f1b95-c828-4ed1-9c54-a309f5ed743c)

## Result:
Thus the inverse of given matrix is successfully solved using python program

