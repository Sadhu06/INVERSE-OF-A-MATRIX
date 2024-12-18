# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign np.array().
### Step 3: 
Using the np.linalg.inverse(),we can find the solution.
### Step 4: 
End the program.
## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Sadhana S 
#RegisterNumber: 24001394
import numpy as np
matrix=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse=np.linalg.inv(matrix)
print(inverse)
```
## Output:
![Output](exp3.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program

