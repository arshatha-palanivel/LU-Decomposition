# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Write a python program.
2. Use numpy as np and open a special library named scipy.
3. Usinng eval data type get the input from the user.
4. Now complete the program and display the output and end the program.

## Program:
(i) To find the L and U matrix
```
/*
##Program to find the L and U matrix.
##Developed by: Arshatha P
##RegisterNumber: 22009104
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
##Program to find the LU Decomposition of a matrix.
##Developed by: Arshatha P
##RegisterNumber: 22009104
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
![lu decomposition](/LU%201.png)
![output](/LU%202.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

