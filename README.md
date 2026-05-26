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
Python
## Register No: 212224040118
## Developed By: HITHESHHWARAN A R
# 1-Norm of a Matrix
```
'''
program to find the 1-Norm of a matrix.
Developed by: HITHESHHWARAN A R
RegisterNumber: 212224040118
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: HITHESHHWARAN A R
RegisterNumber: 212224040118
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```

# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
<img width="1068" height="602" alt="image" src="https://github.com/user-attachments/assets/5beb4ebc-fe5f-42fa-85e8-08ec26f0d717" />


### 2-Norm of a Matrix
<img width="1065" height="600" alt="image" src="https://github.com/user-attachments/assets/1ae2c4cd-14d2-4446-be10-fd6d70d5a9fb" />


### Infinity Norm of a Matrix
<img width="1056" height="601" alt="image" src="https://github.com/user-attachments/assets/b1cbf0e6-4ac1-4b91-9347-ad05624a6f42" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
