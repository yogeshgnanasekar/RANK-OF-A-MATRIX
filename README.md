# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.solve(), we can find the solutions.

### Step 4:
End the program 
## Program:
#Program to find the rank of a matrix.
#Developed by:Yogesh G
#RegisterNumber:212225100061
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[5, -3, -10],
              [2,  2,  -3],
              [-3, -1, 5]])

rank = np.linalg.matrix_rank(A)

print(rank)
## Output:
<img width="519" height="548" alt="Screenshot 2026-06-01 120834" src="https://github.com/user-attachments/assets/64c5cb95-e873-4238-b8c8-ec9e5cdf4f84" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

