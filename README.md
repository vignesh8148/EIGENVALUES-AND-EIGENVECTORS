# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: vignesh.k
#RegisterNumber:25018207
import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0] ])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1319" height="295" alt="Screenshot 2025-11-24 175557" src="https://github.com/user-attachments/assets/95c55c09-5590-43df-87f8-7d3d96c185be" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
