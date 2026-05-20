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
inf_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(inf_matrix))



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(inf_matrix))



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
<br><img width="550" height="150" alt="image" src="https://github.com/user-attachments/assets/8dd2068b-2c76-442a-b03d-436426f5144c" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="502" height="203" alt="image" src="https://github.com/user-attachments/assets/a39c05cc-46ad-451f-889f-d16c252bd504" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="542" height="157" alt="image" src="https://github.com/user-attachments/assets/33ebae12-6ad3-4b52-81dd-2b25e7b39557" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
