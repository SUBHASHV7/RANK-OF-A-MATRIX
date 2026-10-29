# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
r=np.linalg.matrix_rank(A)
print(r)
```
## Output:
<img width="1043" height="502" alt="image" src="https://github.com/user-attachments/assets/90b806e1-b03b-47f4-a5cb-284414f342f9" />

<img width="1312" height="291" alt="image" src="https://github.com/user-attachments/assets/f549e68d-9010-4e0e-971f-7f140fb14084" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

