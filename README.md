# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import numpy package as np.
### Step 2: Create a matrix using array() function.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Get the output and end the program.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Ronick Aakshath P
#RegisterNumber: 22007303

import numpy as np

a = np.array([[3, 2, 5], [1, 1, 2], [3, 3, 6]])
mat_rnk = np.linalg.matrix_rank(a)
print(mat_rnk)
```
## Output:
![output for rank of a matrix](/Output_for_Mat_Rnk.png)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
