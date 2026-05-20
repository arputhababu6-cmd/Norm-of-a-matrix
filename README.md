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
matrix=eval(input())
o_m=np.linalg.norm(matrix,1)
print("{:.2f}".format(o_m))



# 2-Norm of a Matrix
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
<br><img width="560" height="148" alt="image" src="https://github.com/user-attachments/assets/99f2ae02-8fb0-4de1-8845-5a57bb5d3939" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="527" height="191" alt="image" src="https://github.com/user-attachments/assets/3403248c-4963-4e65-afd7-2800d2167063" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="564" height="155" alt="image" src="https://github.com/user-attachments/assets/9944046a-d172-4933-84da-b224bb14715d" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
