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
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6c908320-d433-4214-ad3c-fad8a94f614d" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ee5d014c-8f88-4ae8-b43b-31db44607560" />


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

