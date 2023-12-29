# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1.first use the import 
2.second use the numpy operatore
3.thrid i use the print statment 
4.i got the output
```
## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Abdul kalaam k m
RegisterNumber:23005114 

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Abdul kalaam k m
RegisterNumber:23005114 


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![Screenshot 2023-12-29 160342](https://github.com/dfghytr/LU-Decomposition/assets/138970628/46453490-0674-4aea-8e5e-969e6ad4a39d)

![Screenshot 2023-12-29 160355](https://github.com/dfghytr/LU-Decomposition/assets/138970628/cfb8d075-612f-468f-a06f-85480e61a81a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

