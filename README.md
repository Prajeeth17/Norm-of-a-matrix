# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step 1:
Get the input matrix using np.array()   
## Step 2:
Find the 2-norm of the matrix using np.linalg.norm()
## Step 3:
Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 22002267
# Developed By: Prajeeth K T
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of="{:.2f}".format(ans)
print(norm_of)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of="{:.2f}".format(ans)
print(norm_of)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of="{:.2f}".format(ans)
print(norm_of)
```

## Output:
### 1-Norm of a Matrix
![](./1%20norm.jpg)

### 2-Norm of a Matrix
![](2%20norm.jpg)

### Infinity Norm of a Matrix
![](infinity%20norm.jpg)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
