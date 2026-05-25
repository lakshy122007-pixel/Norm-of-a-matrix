# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Start the program and import the NumPy library.
2. Read the matrix elements from the user and store them in a matrix.
3. Use numpy.linalg.norm(matrix,1) to find the 1-norm of the matrix.
4. Display the result in two decimal places and stop the program.
## Program:
```Python
# Register No: 212225240076
# Developed By: Lakshiya Rajkumar
# 1-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix

```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,ord=np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br><img width="1415" height="835" alt="WhatsApp Image 2026-05-25 at 7 28 08 PM" src="https://github.com/user-attachments/assets/657ef719-1f59-4394-9566-ab9269a198cb" />


### 2-Norm of a Matrix
<br>
<br>
<br><img width="1447" height="831" alt="WhatsApp Image 2026-05-25 at 7 28 26 PM" src="https://github.com/user-attachments/assets/549cde76-c4b4-43dc-96ac-7ed9b1c16ae3" />


### Infinity Norm of a Matrix
<br>
<br>
<br><img width="1429" height="824" alt="image" src="https://github.com/user-attachments/assets/1368ad9c-f7b8-401f-81ca-7f7817bb6ea2" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
