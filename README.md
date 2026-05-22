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
/*
Program to find the L and U matrix.
Developed by: Moogethshivan G G 
RegisterNumber: 212225040259
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Moogethshivan G G 
RegisterNumber: 212225040259
*/
```

## Output:
![lu decomposition]()
1.
'''Program to find L and U matrix using LU decomposition.
Developed by: Moogethshivan G G 
RegisterNumber: 212225040259
'''
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
import scipy.linalg
A = np.array(eval(input()), dtype=float)
P, L, U = scipy.linalg.lu(A)
print(L)
print(U)

2
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
import scipy.linalg

A = np.array(eval(input()),dtype=float)
b = np.array(eval(input()),dtype=float)

lu,piv=scipy.linalg.lu_factor(A)
x=scipy.linalg.lu_solve((lu,piv),b)
print(x)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

