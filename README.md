# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import libraries import numpy as np
2. Get input matrix from user
3. Find L and u decomposition
4. Print L and U
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:A.Hari Veera Prasad 
RegisterNumber:23009466
from scipy.linalg import lu
import numpy as np
arr=eval(input())
a=np.array(arr)
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:A.Hari Veera Prasad  
RegisterNumber::23009466
 # To print X matrix (solution to the equations)
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)

*/
```

## Output:
#  To find the L and U matrix
![image](https://github.com/Hariveeraprasad-2006/LU-Decomposition/assets/145049988/6815ecaa-2d35-4ba4-93de-8d0779325fae)

# Program to find the LU Decomposition of a matrix.
![image](https://github.com/Hariveeraprasad-2006/LU-Decomposition/assets/145049988/c419fb63-14c5-49ab-965a-b0503701e3b5)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

