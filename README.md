# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2.  Prepare the lists from each linear equations and assign in np.array()
3.   Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
4.   End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Udhaya Giri V
RegisterNumber: 25015458
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Udhaya Giri V
RegisterNumber: 25015458
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,pivot=lu_factor(a)
x=lu_solve((lu,pivot),b)
print(x)
*/
```

## Output:
<img width="1468" height="851" alt="image" src="https://github.com/user-attachments/assets/705f7a8d-b1f2-402a-a70a-d69d7771b6fb" />
<img width="1231" height="581" alt="Screenshot 2025-12-05 090812" src="https://github.com/user-attachments/assets/68e20f5e-e227-4154-af2f-91d6a5dc3431" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

