# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import Required Libraries
2. User Input and Array Creation
3. Apply LU decomposition
4. Print Lower and Upper Triangular Matrices

## Program:
### (i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Gnanendran N
RegisterNumber: 23006661
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
### (ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Gnanendran N
RegisterNumber: 23006661
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
![code](https://github.com/GnanendranN/LU-Decomposition/assets/138955207/cdb2ef95-b3e7-49b3-a5fc-0b4e514fa8db)

![code1](https://github.com/GnanendranN/LU-Decomposition/assets/138955207/fad596e2-0931-468f-b768-740445fe307a)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

