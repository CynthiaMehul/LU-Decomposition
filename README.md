# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Get the input matrix using np.array()
2.Find the 2-norm of the matrix using np.linalg.norm()
3. Print the noem of the matris in two decimals places. 
4. End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Cynthia Mehul J
RegisterNumber: 23009725
*/
import numpy as np
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
Developed by: Cynthia Mehul J
RegisterNumber: 23009725
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
![label](/Output%20LU%201.jpg)
![label](/Output%20LU%202.jpg)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

