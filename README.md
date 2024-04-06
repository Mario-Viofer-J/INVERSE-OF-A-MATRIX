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
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program
## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: Mario Viofer J
#RegisterNumber: 212223100032
import numpy as np
matrix = np.array([[6, 2, 3], [3, 1, 1], [10, 3, 4]])
inverse_matrix = np.linalg.inv(matrix)
print(inverse_matrix)
~~~
## Output:
![image](https://github.com/Mario-Viofer-J/INVERSE-OF-A-MATRIX/assets/144979232/c4c08b13-fcda-4422-ac88-107f0a91bfec)

## Result:
Thus the inverse of given matrix is successfully solved using python program

