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
# Register No:
# Developed By:
# 1-Norm of a Matrix
##The 1 norm of a matrix (often called the maximum column sum norm) is
## calculated as the maximum sum of the absolute values of the elements in each column

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Srinithi Muthukumar
RegisterNumber: 212224240161
'''
import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
# Type your code here



# Infinity Norm of a Matrix
## NAME: Srinithi Muthukumar
## REGISTER NUMBER: 212224240161

import numpy as np
mat = np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="1096" height="925" alt="Screenshot 2025-10-31 184529" src="https://github.com/user-attachments/assets/09c446d7-a634-4d21-806f-192aee7d9820" />

### 2-Norm of a Matrix
<img width="1295" height="938" alt="Screenshot 2025-10-31 184628" src="https://github.com/user-attachments/assets/8864f683-a527-406c-8b99-9714fe4c00a1" />


### Infinity Norm of a Matrix
<img width="1189" height="907" alt="Screenshot 2025-10-31 184710" src="https://github.com/user-attachments/assets/bc88668e-ddbd-4805-9c2c-651f37522b5b" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
