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
# Register No:23013723
# Developed By:Kishore B
# 1-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-12-19 150149](https://github.com/codedbykishore/Norm-of-a-matrix/assets/147139122/60ace5e5-26dd-43af-9b5b-16df38a95953)
<br>
### 2-Norm of a Matrix

![Screenshot 2023-12-19 151321](https://github.com/codedbykishore/Norm-of-a-matrix/assets/147139122/ae5ed460-b253-4f5d-acab-a295ede5966b)
<br>
### Infinity Norm of a Matrix

![Screenshot 2023-12-19 151341](https://github.com/codedbykishore/Norm-of-a-matrix/assets/147139122/ceef0fb3-c13b-475c-a738-4a00c9e6e27f)
<br>
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
