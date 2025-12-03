# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# 1-Norm of a Matrix
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by :Hari Krishnan S
Register number: 212224100020
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: HIRUTHIK SUDHAKAR
RegisterNumber: 212223240054 
'''
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)



# Infinity Norm of a Matrix

'''
Program to find Infinity norm of a matrix.
Developed by: HIRUTHIK SUDHAKAR
RegisterNumber: 212223240054 
'''
import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix

<img width="1315" height="531" alt="image" src="https://github.com/user-attachments/assets/43aae266-febb-449c-9fde-350736f22dbb" />


### 2-Norm of a Matrix

<img width="1297" height="558" alt="image" src="https://github.com/user-attachments/assets/4eb76824-66f0-4e9a-bbde-8103d96820dc" />


### Infinity Norm of a Matrix


<img width="1298" height="526" alt="image" src="https://github.com/user-attachments/assets/82ea4863-9f12-4b5f-87c7-95a2f45c2779" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
