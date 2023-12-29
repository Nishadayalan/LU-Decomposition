# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package and scipy.linalg impot lu.
2. Get input from the user and print L and U matrix by print.
3. Define a packages as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in that value.
4. print the variable X.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NISHA.D
RegisterNumber: 212223230143

#to print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NISHA.D
RegisterNumber: 212223230143
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
To find the L and U matrix
![Alt text](<Screenshot 2023-12-29 210129.png>)

 To find the LU Decomposition of a matrix


![Alt text](<Screenshot 2023-12-29 210202.png>)








## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

