# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: Prashanth.K
RegisterNumber: 212223230152


import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Prashanth.K
RegisterNumber: 212223230152

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
B=np.array(eval(input()))
C=np.linalg.solve(A,B)
print(C)

```

## Output:
(i)To find the L and U matrix

![Screenshot 2024-04-06 143645](https://github.com/PRASHANTHRATHI/LU-Decomposition/assets/145743120/60bcdfd1-ad62-4f03-a77e-ca73f851f088)
![Screenshot 2024-04-06 143655](https://github.com/PRASHANTHRATHI/LU-Decomposition/assets/145743120/979750b5-e0cb-4dca-85e5-0477ee9c65e3)

(ii)To find the LU Decomposition of a matrix

![Screenshot 2024-04-06 143707](https://github.com/PRASHANTHRATHI/LU-Decomposition/assets/145743120/0eb2a297-f10c-4471-b6bb-183f58165019)
![Screenshot 2024-04-06 143714](https://github.com/PRASHANTHRATHI/LU-Decomposition/assets/145743120/85a170ad-0cb8-43b5-81b8-bff048a71315)







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

