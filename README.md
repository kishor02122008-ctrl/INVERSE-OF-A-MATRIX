# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy library 
### Step 2: Define the square matrix A using np.array()
### Step 3: Compute the inverse using np.linalg.inv(A) and store it in B
### Step 4: Print the inverse matrix B

## Program:import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A=np.array([[6,2,3],[3,1,1],[10,3,4]])

B=np.linalg.inv(A)

print(B)

## Output:<img width="555" height="743" alt="{E39C1E35-071A-4E6D-A0D8-378C58DEE356}" src="https://github.com/user-attachments/assets/9889c8bc-591b-4009-ae30-1b7fa4e54a9e" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

