# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Initialize L and U matrices
2. For each row ,eliminate variables below the pivot
3. Update L and U matrices
4. Return L and U

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: K.Preethi
RegisterNumber: 24900485
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: K.Preethi 
RegisterNumber: 24900485
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv= lu_factor(A)
X= lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
![lu decomposition](![Alt text](<Screenshot 2024-12-08 193636.png>))
![Alt text](<Screenshot 2024-12-08 193731.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

