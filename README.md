# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Define the package as scipy.linalg import lu.
Step 2: Get input from user and print L and U matrix by 'print'.
Step 3: Define a package as "from scipy.linalg import lu_factor, lu_solve" and create
Step 4: Print the variable 'X'.

## Program:
(i) To find the L and U matrix
``` 
/*
Program to find the L and U matrix.
Developed by: AMIRTHA VARSHINI M 
RegisterNumber: 24901093

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: AMIRTHA VARSHINI M
RegisterNumber: 24901093

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
i) To find the L and U matrix.
![Screenshot (2008)](https://github.com/user-attachments/assets/b2c7280a-007e-41a0-a436-ed5cae01b78d)


ii) To find the LU Decomposition of a matrix.
![Screenshot (2009)](https://github.com/user-attachments/assets/deb4a361-258e-4834-91c7-78ac1c035085)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

