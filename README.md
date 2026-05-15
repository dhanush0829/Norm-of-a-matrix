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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by:Dhanush M
#RegisterNumber: 212225230051
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
mat = np.array(eval(input())) 
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
<img width="778" height="656" alt="image" src="https://github.com/user-attachments/assets/6e9f87ad-c7c8-481c-a81c-e7457a2c5718" />

### 2-Norm of a Matrix
<img width="700" height="690" alt="image" src="https://github.com/user-attachments/assets/00e0d6cb-4ad4-439f-8cdb-3bcec7861d24" />


### Infinity Norm of a Matrix
<img width="703" height="653" alt="image" src="https://github.com/user-attachments/assets/215a192b-08d5-4035-8550-bd948c2f9c6c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
