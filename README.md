# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' . 
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable 
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: G.Ramanujam
RegisterNumber: 212224240129
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
Developed by: G.Ramanujam
RegisterNumber: 212224240129
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
<img width="1197" height="917" alt="Screenshot 2025-08-28 092016" src="https://github.com/user-attachments/assets/635aea78-c6ad-4ebb-b318-870cf97701ed" />
<img width="1204" height="588" alt="Screenshot 2025-08-28 092033" src="https://github.com/user-attachments/assets/92b254ab-b329-42cb-a24f-7abe8947117c" />
<img width="1212" height="845" alt="Screenshot 2025-08-28 092047" src="https://github.com/user-attachments/assets/cb17394a-f773-4689-ac86-1bdc19c8a205" />
<img width="1223" height="330" alt="Screenshot 2025-08-28 092100" src="https://github.com/user-attachments/assets/9c826e36-caa1-4967-b999-e9c0755ea541" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

