# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.
2. Import numpy as np.
3. Using eval get the input matrix.
4. Declare the formula for lu decompostion and obtain the result.
5. End the program. 

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: Kishore N
#RegisterNumber: 212223230106

#To find L and U matrix
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: Kishore N
#RegisterNumber: 212223230106

#To print X matrix(solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv= lu_factor(a)
x=lu_solve((lu,piv),b)
print (x)
```

## Output:
![lu decomposition]()

### To print L and U matrix
![Screenshot 2024-05-13 123638](https://github.com/kishorenagarajan08/LU-Decomposition/assets/155753188/968ff1eb-9efd-482e-9d8e-42152dbf2b8c)

#### To print X matrix (solution to the equations)
![Screenshot 2024-05-13 123710](https://github.com/kishorenagarajan08/LU-Decomposition/assets/155753188/9a33f8ea-6c01-4b5a-a79a-06748c4acbfc)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

