# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2: 
prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the solution.
### Step 4: 
End the program.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by:vignesh.v
#RegisterNumber:23004027

import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
b=np.linalg.matrix_rank(a)
print(b)

```
## Output:
![EXM2](https://github.com/23004027/RANK-OF-A-MATRIX/assets/138956447/ea8fcf61-cfe6-4f62-b189-9dd2da34eee1)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

