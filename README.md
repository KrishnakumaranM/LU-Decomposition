# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
## Program 1:
1. Import numpy library
2. Import lu function from scipy library.
3. Solve LU decompostion using lu() function
4. print the value
## Program 2:
1. Import numpy
2. From scipy.linalg import lu,lu_factor,lu_solve respectively
3. Get the input of matrix values from user using eval
4. Print and solce LU decomposition using lu_solve() function
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:KRISHNA KUMARAN M
RegisterNumber: 212224110033
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
Developed by:KRISHNA KUMARAN M 
RegisterNumber:212224110033
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![Screenshot 2025-04-12 133952](https://github.com/user-attachments/assets/5e7226e1-1a8e-47d8-9c52-a643ac514487)

![Screenshot 2025-04-12 134014](https://github.com/user-attachments/assets/851b853c-7d98-41b7-8d15-3fe7bc4f3ff2)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

