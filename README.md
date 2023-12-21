# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 1-Norm, 2-norm and Infinity norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212223240062
# Developed By: Joel John Jobinse
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
![maths-exp7-1](https://github.com/joeljohnjobinse/Norm-of-a-matrix/assets/138955488/ff975e3f-cbb1-4fbf-aa73-a00a2bb267bd)


### 2-Norm of a Matrix
![maths-exp7-2](https://github.com/joeljohnjobinse/Norm-of-a-matrix/assets/138955488/760bdb20-53b9-4d8e-868a-59ef85cecb78)


### Infinity Norm of a Matrix
![maths-exp7-3](https://github.com/joeljohnjobinse/Norm-of-a-matrix/assets/138955488/c2204cfa-8d1b-4fd5-bde2-9cb310ca21f9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
