# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

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

