# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: R N SOMNATH
RegisterNumber: 24000580
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by:R N SOMNATH 
RegisterNumber: 24000580
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x) 
*/
```

## Output:
![lu decomposition]()
![image](https://github.com/user-attachments/assets/8e0f9ae0-3e79-46f5-9ab5-0d9bdae558b6)
![image](https://github.com/user-attachments/assets/f39c5484-9179-4ac4-b497-0c9f810fbfbf)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

