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
# Register No: 212225040079
# Developed By: DINESH D

# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))

# 2-Norm of a Matrix
#*## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.*#


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))

# Infinity Norm of a Matrix


import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))

```
## Output:
### 1-Norm of a Matrix
<img width="1511" height="920" alt="image" src="https://github.com/user-attachments/assets/6495f790-7c00-4375-9fb9-ad09d76bebbd" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1491" height="921" alt="image" src="https://github.com/user-attachments/assets/9d6d23ab-d767-4288-b08d-4efe9d6c4643" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1803" height="845" alt="image" src="https://github.com/user-attachments/assets/453f0198-f3fe-42e1-abd3-ed48416e60a5" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
