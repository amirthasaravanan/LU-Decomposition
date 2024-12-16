# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
Step 1: Define the package as scipy.linalg import lu.
Step 2: Get input from user and print L and U matrix by 'print'.
Step 3: Define a package as "from scipy.linalg import lu_factor, lu_solve" and create
Step 4: Print the variable 'X'.
```

## Program:
(i) To find the L and U matrix
``` 

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

```

## Output:
i) To find the L and U matrix.
![ED EX 5 ONE](https://github.com/user-attachments/assets/b5d67300-7dde-4a6d-ab6b-1478635bbbc8)


ii) To find the LU Decomposition of a matrix.
![ED EXP 5 TWO](https://github.com/user-attachments/assets/9742cef3-6043-4aaa-934d-9935396e6a3b)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

