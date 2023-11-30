# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1 : Get the dimensions of the matrix
### Step 2 : Initialize matrices L and U
### Step 3 : Perform LU decomposition
### Step 4 : Return the decomposed matrices L and U


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SUDHARSANA KUAMR S R
RegisterNumber: 23007374
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SUDHARSANA KUMAR S R 
RegisterNumber: 23007374
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = eval(input())
b = eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
Output 1:
![image](https://raw.githubusercontent.com/sudharsanakumar18/LU-Decomposition/main/maths%20exp%2005%20a.png)

Output 2:
![image](https://raw.githubusercontent.com/sudharsanakumar18/LU-Decomposition/main/maths%20exp%205%20b.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

