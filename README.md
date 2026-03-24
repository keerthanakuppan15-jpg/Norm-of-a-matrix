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
# Register No:212225230137
# Developed By:keerthana k
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



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
<br><img width="1263" height="773" alt="Screenshot 2026-03-24 235409" src="https://github.com/user-attachments/assets/32dbcfb0-88bf-40c3-8ce9-de9a6c427c06" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br><img width="1280" height="820" alt="Screenshot 2026-03-24 235428" src="https://github.com/user-attachments/assets/76accef6-f96d-476f-9009-9874701ec7d8" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="1271" height="760" alt="Screenshot 2026-03-24 235453" src="https://github.com/user-attachments/assets/724bb730-ad12-4acb-9c93-34755b9dbb80" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
