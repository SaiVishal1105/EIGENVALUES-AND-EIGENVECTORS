# EIGENVALUES-AND-EIGENVECTORS
NAME: SAI VISHAL D<br>
REF.NO: 23013576
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2 : 
Prepare the lists from linear equation and assign in np.array().
### Step 3 : 
Using the np.linalg.eig(), we can find the eigen values and eigen vectors of the given matrix.
### Step 4 : 
End the Program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SAI VISHAL D
#RegisterNumber: 23013576

import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values, vectors))
```

## Output:
![Alt text](<Screenshot 2023-12-13 203146.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
