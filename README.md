# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy module to use the built in functions for calculations. 
2. From scipy.linalg import lu to find L and U matrix.
3. Get input from the user and apply lu function. 
4. Print L for L matrix and print U for U matrix.
5. End the program.

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

