# EIGENVALUES-AND-EIGENVECTORS
DEVELOPED BY : PRIYANKA P 
REG NO. : 212224230212
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: PRIYANKA P
#RegisterNumber: 212224230212
import numpy as np
A = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

```
## Output:
<img width="1920" height="1200" alt="Screenshot 2025-08-19 212508" src="https://github.com/user-attachments/assets/c8dac0f3-b4f2-420e-9664-9043ae99e47a" />
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
