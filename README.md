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
# Register No:22002839
# Developed By:kaviya shree
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
n=np.linalg.norm(a,2)
print("{:.2f}".format(n))


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))



```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/120553351/215090883-e692e2d2-993d-47c6-9eb1-ac888d94ab6e.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/120553351/215090950-c645a0cb-e71d-40e0-8160-3191d3362714.png)
### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/120553351/215091023-571ba549-037d-4d9d-b5b1-2f7f1815d752.png)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
