# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy using import numpy as np
2. import scipy by using from scipy.linalg import lu
3. to find L and U use P,L,U=lu(A)
4. to find LU decomposition use x=lu_solve((lu,pivot),B)

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ASHWIN BAALAJI V K
RegisterNumber: 25011987
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
Developed by: ASHWIN BAALAJI V K
RegisterNumber: 25011987
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
<img width="1916" height="1054" alt="Screenshot 2025-11-20 172058" src="https://github.com/user-attachments/assets/0b08fe46-c50d-40a3-ac65-48af1115f544" />
<img width="1918" height="1038" alt="image" src="https://github.com/user-attachments/assets/5367ae54-c161-449f-8195-bc7636d7c359" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

