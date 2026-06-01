# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program.
### Step 2: Create the matrix with the given numbers.
### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the answers and stop.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: athif
#RegisterNumber:212225040239
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[2, 2],
              [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1282" height="263" alt="Screenshot 2026-06-01 111038" src="https://github.com/user-attachments/assets/dd949224-768f-470a-8883-d79ee1513503" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
