# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into arrays.

2.Calculate elements of L and U.

3.Print elements of L and U.

4.Find V by solving LV=B by forward substitution. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Renuga.S 
RegisterNumber:212222230118
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Renuga.S 
RegisterNumber:212222230118
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![L and U](https://github.com/RENUGASARAVANAN/LU-Decomposition/assets/119292258/3a5b6db5-020d-4b16-a125-ed03051de9e4)

![LU](https://github.com/RENUGASARAVANAN/LU-Decomposition/assets/119292258/72ed4844-4a10-4d34-9635-574183c5af98)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

