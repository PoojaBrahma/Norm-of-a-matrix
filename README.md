# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	
 1. Get the input matrix using np.array().

2. Find the 2-norm of the matrix using np.linalg.norm()
	
 3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 24900687
# Developed By: P.Pooja
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-12-04 140845](https://github.com/user-attachments/assets/45132e37-98a9-4670-976f-876fc6731468)


### 2-Norm of a Matrix

![Screenshot 2024-12-04 140859](https://github.com/user-attachments/assets/e1e33384-8da2-4b1c-9df3-ee6acd6d6fee)


### Infinity Norm of a Matrix

![Screenshot 2024-12-04 141034](https://github.com/user-attachments/assets/418cddb4-b308-4221-bc2e-11ca01176039)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
