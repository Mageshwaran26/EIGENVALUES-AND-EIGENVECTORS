# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : First IMport Numpy Using import
### Step 2: Then Convert The List of Matrix Into Array using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Lastly print the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mageshwaran T.A
#RegisterNumber: 212224230146

import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1315" height="137" alt="Screenshot 2026-02-05 091227" src="https://github.com/user-attachments/assets/0cc7e086-3947-491f-aa35-5e3d2cad3c9a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
