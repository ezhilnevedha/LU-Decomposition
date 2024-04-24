# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. step1: Define the package as scipy.linalg import lu

2. step2: Get input from user and print L and U matrix by 'print'

3. step3: Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4. step4: print the variable 'X'

5. step5: End the program.


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: EZHIL NEVEDHA.K
RegisterNumber: 212223230055
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: EZHIL NEVEDHA.K
RegisterNumber: 212223230055
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![alt text](<Screenshot 2024-04-24 151512.png>)

![alt text](<Screenshot 2024-04-24 151526.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

