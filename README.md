# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Find the l and u matirx by using numpy and linalg from scipy
2. Print the l matrix and u matirx
3. Find the lu decomposition by using numpy and lu_factor and lu_solve
4. Print the the following matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SHANKAR SB
RegisterNumber: 25017085
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
Developed by: SHANKAR SB
RegisterNumber: 25017085
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1251" height="768" alt="Screenshot 2025-11-27 105801" src="https://github.com/user-attachments/assets/5562ed3f-a5ff-4331-a6b3-f4b946fadda4" />
<img width="851" height="533" alt="Screenshot 2025-11-27 105825" src="https://github.com/user-attachments/assets/4626370f-7456-4785-9319-7a73d5ff9de4" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

