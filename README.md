# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S.D Surendar
RegisterNumber: 212224110052

import  numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S.D Surendar
RegisterNumber: 212224110052


import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
L,P=lu_factor(a)
x=lu_solve((L,P),b)
print(x)
```

## Output:
<img width="1037" height="761" alt="image" src="https://github.com/user-attachments/assets/f6d1801f-6391-4ccb-aaca-c3351b55b329" />

<img width="1034" height="572" alt="image" src="https://github.com/user-attachments/assets/b18a642c-59fe-4baa-82f6-ae195a2b5019" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

