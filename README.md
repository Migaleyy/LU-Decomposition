# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation
2.Prepare the lists from each linear equations and assign in np.array()
3.Using the scipy.linalg and imort lu_fator and lu_solve we get the values
4.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Migal G Arunadann
RegisterNumber: 212222110025
*/
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Migal G Arunadann
RegisterNumber: 212222110025
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
1

![image](https://github.com/Migaleyy/LU-Decomposition/assets/118262199/dd179d69-0fff-421c-8047-80b8f7ae7f35)
2

![image](https://github.com/Migaleyy/LU-Decomposition/assets/118262199/0e613d82-37a4-4ed9-8997-df116a841909)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

