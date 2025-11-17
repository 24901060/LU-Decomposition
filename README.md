# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Algorithm to Find L and U Matrices (LU Decomposition)

### Step 1: Import the required libraries (numpy and scipy.linalg).
### Step 2: Read the input matrix using np.array().
### Step 3: Using the lu() function, decompose the matrix into P, L, and U matrices.
### Step 4: Print the L and U matrices.

### Algorithm to Solve a Matrix Using LU Decomposition

### Step 1: Import the required libraries (numpy and scipy.linalg).
### Step 2: Read matrix A and vector B using np.array().
### Step 3: Use lu_factor() to get the LU decomposition and pivot values.
### Step 4: Use lu_solve() to compute the solution for X, and print the result.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Praveen S
RegisterNumber: 212224230206
'''

import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U = lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Praveen S
RegisterNumber: 212224230206
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
Result = lu_solve((lu,pivot),B)
print(Result)

```

## Output:
<img width="1317" height="961" alt="image" src="https://github.com/user-attachments/assets/220256fe-8fb2-44ce-b8b2-ed164e3ccd7b" />

<img width="1314" height="794" alt="image" src="https://github.com/user-attachments/assets/6142ed87-1531-420c-a257-a0d845f788d7" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

